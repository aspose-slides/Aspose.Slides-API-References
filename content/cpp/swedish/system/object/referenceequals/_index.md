---
title: ReferenceEquals()
second_title: Aspose.Slides för C++ API-referens
description: "Specialisering av Object::ReferenceEquals för fallet med sträng och nullptr."
type: docs
weight: 261
url: /sv/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method


Specialisering av [Object::ReferenceEquals](./) för fallet med sträng och nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) att jämföra med nullptr. |

### Returvärde

true if string is null, false otherwise.

## Object::ReferenceEquals(String const\&, String const\&) method


Specialisering av [Object::ReferenceEquals](./) för fallet med strängar.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Första strängen att jämföra. |
| str2 | [String](../../string/) const\& | Andra strängen att jämföra. |

### Returvärde

true if strings match, false otherwise.

## Object::ReferenceEquals(ptr const\&, ptr const\&) method


Jämför objekt efter referens.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Första pekaren att jämföra. |
| objB | [ptr](../ptr/) const\& | Andra pekaren att jämföra. |

### Returvärde

True if pointers match and false otherwise.

## Object::ReferenceEquals(T const\&, T const\&) method


Jämför objekt efter referens.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T const\& | Första objektet att jämföra. |
| objB | T const\& | Andra objektet att jämföra. |

### Returvärde

True if object addresses match and false otherwise.

## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Referensjämför värdetypobjekt med nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T const\& | Första objektet att jämföra. |

### Returvärde

Always returns false as value types cannot be nulled.

## Se även

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)