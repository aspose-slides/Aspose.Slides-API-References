---
title: GetType()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Implementuje překlad typeof(). Přetížení pro chytré ukazatele.
type: docs
weight: 1
url: /cs/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) metoda

Implementuje překlad typeof(). Přetížení pro chytré ukazatele.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pro získání [TypeInfo](../../typeinfo/). |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující finální třídu předaného objektu.

## ObjectType::GetType(const T\&) metoda

Implementuje překlad typeof(). Přetížení pro struktury.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ struktury. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pro získání [TypeInfo](../../typeinfo/). |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující finální třídu předaného objektu.

## ObjectType::GetType(const T\&) metoda

Implementuje překlad typeof(). Přetížení pro výjimky.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ výjimky. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pro získání [TypeInfo](../../typeinfo/). |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující finální třídu předaného objektu.

## ObjectType::GetType(const T) metoda

Implementuje překlad typeof(). Přetížení pro primitivní typy.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Primitivní typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T | IGNOROVÁNO |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující typ předaného objektu.

## ObjectType::GetType(const T) metoda

Implementuje překlad typeof(). Přetížení pro typy [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Nullable](../../nullable/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T | IGNOROVÁNO |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující typ předaného objektu.

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro primitivní typy.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Primitivní typ. |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující zadaný typ.

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro typy výčtů.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Primitivní typ. |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující zadaný typ.

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro struktury a ukazatele.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Primitivní typ. |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující zadanou strukturu.

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Nullable](../../nullable/). |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující zadanou strukturu.

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ MutlicastDelegate. |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující zadanou strukturu.

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro struktury a ukazatele.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Primitivní typ. |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující zadanou strukturu nebo typ ukazovaného objektu, pokud je voláno pro [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) metoda

Implementuje překlad typeof(). Přetížení pro řetězcový typ.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Primitivní typ. |

### Návratová hodnota

Konstantní reference na strukturu [TypeInfo](../../typeinfo/) popisující typ [String](../../string/).

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda

Implementuje překlad typeof(). Přetížení pro [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Viz také

* Třída [ObjectType](../)
* Třída [TypeInfo](../../typeinfo/)
* Třída [String](../../string/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsNullable](../../isnullable/)
* Struktura [IsBoxable](../../isboxable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)