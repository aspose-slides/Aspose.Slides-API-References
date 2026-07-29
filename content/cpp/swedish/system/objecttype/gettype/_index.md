---
title: GetType()
second_title: Aspose.Slides för C++ API-referens
description: Implementerar typeof() översättning. Överlagring för smarta pekare.
type: docs
weight: 1
url: /sv/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) metod


Implementerar typeof() översättning. Överlagring för smarta pekare.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Pekarobjekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att hämta [TypeInfo](../../typeinfo/) för. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den slutgiltiga klassen av det överförda objektet.

## ObjectType::GetType(const T\&) metod


Implementerar typeof() översättning. Överlagring för strukturer.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Strukturtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att hämta [TypeInfo](../../typeinfo/) för. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den slutgiltiga klassen av det överförda objektet.

## ObjectType::GetType(const T\&) metod


Implementerar typeof() översättning. Överlagring för undantag.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Undantagstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att hämta [TypeInfo](../../typeinfo/) för. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den slutgiltiga klassen av det överförda objektet.

## ObjectType::GetType(const T) metod


Implementerar typeof() översättning. Överlagring för primitiva typer.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T | IGNORED |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den slutgiltiga klassen av det överförda objektet.

## ObjectType::GetType(const T) metod


Implementerar typeof() översättning. Överlagring för [Nullable](../../nullable/) typer.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T | IGNORED |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den slutgiltiga klassen av det överförda objektet.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för primitiva typer.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade typen.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för enum-typer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade typen.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för strukturer och pekare.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den angivna strukturen.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade strukturen.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | MutlicastDelegate typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade strukturen.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för strukturer och pekare.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den angivna strukturen eller den pekade typen om anropad för [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) metod


Implementerar typeof() översättning. Överlagring för string-typ.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### Returvärde

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver [String](../../string/) typ.

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metod


Implementerar typeof() översättning. Överlagring för [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se också

* Klass [ObjectType](../)
* Klass [TypeInfo](../../typeinfo/)
* Klass [String](../../string/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Struktur [IsBoxable](../../isboxable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)