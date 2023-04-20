---
title: IsDefined()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the specified value is a member of enumeration type E.
type: docs
weight: 27
url: /cpp/system/enum/isdefined/
---
## Enum::IsDefined(E) method


Determines whether the specified value is a member of enumeration type **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | E | The value to check |

### Return Value

True if **value** is a member of enumeration **E**, otherwise - false

## Enum::IsDefined(T) method


Determines whether the specified value is a member of enumeration type **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to check |

### Return Value

True if **value** is a member of enumeration **T**, otherwise - false

## Enum::IsDefined(const String\&) method


Determines if the value with the specified name is among members of enum **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../string/)\& | The name to check |

### Return Value

True if a member of enum **E** with the specified name exists.

## See Also

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)