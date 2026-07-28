---
title: GetType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Implementuje translację typeof(). Przeciążenie dla inteligentnych wskaźników.
type: docs
weight: 1
url: /pl/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla inteligentnych wskaźników.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ obiektu wskaźnika. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) aby uzyskać [TypeInfo](../../typeinfo/) dla. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej ostateczną klasę przekazanego obiektu.

## ObjectType::GetType(const T\&) metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla struktur.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ struktury. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) aby uzyskać [TypeInfo](../../typeinfo/) dla. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej ostateczną klasę przekazanego obiektu.

## ObjectType::GetType(const T\&) metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla wyjątków.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ wyjątku. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) aby uzyskać [TypeInfo](../../typeinfo/) dla. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej ostateczną klasę przekazanego obiektu.

## ObjectType::GetType(const T) metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla typów prymitywnych.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ prymitywny. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T | IGNORED |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej typ przekazanego obiektu.

## ObjectType::GetType(const T) metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla typów [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ [Nullable](../../nullable/). |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T | IGNORED |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej typ przekazanego obiektu.

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla typów prymitywnych.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ prymitywny. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej określony typ.

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla typów wyliczeniowych.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ prymitywny. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej określony typ.

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla struktur i wskaźników.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ prymitywny. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej określoną strukturę.

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ [Nullable](../../nullable/). |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej określoną strukturę.

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ MutlicastDelegate. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej określoną strukturę.

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla struktur i wskaźników.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ prymitywny. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej określoną strukturę lub typ wskazywanego obiektu, jeśli wywołano dla [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla typu string.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ prymitywny. |

### Wartość zwracana

Stałe odwołanie do struktury [TypeInfo](../../typeinfo/) opisującej typ [String](../../string/).

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metoda


Implementuje tłumaczenie typeof(). Przeciążenie dla [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Zobacz również

* Klasa [ObjectType](../)
* Klasa [TypeInfo](../../typeinfo/)
* Klasa [String](../../string/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsNullable](../../isnullable/)
* Struktura [IsBoxable](../../isboxable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)