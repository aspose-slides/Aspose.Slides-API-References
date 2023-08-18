---
title: operator>=()
second_title: Aspose.Slides for C++ API Reference
description: Always returns false.
type: docs
weight: 170
url: /system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const method


Always returns false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Return Value

Always - false

## Nullable::operator>=(const T1\&) const method


Determines if the value represented by the current object is greater or equal to the value represented by the specified object by applying [operator>=()](./) to these values.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the value to compare the value represented by the current object with |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to an object to compare the current object with |

### Return Value

True if the value represented by the current object is greater or equal to the value represented by the specified object, otherwise - false

## Nullable::operator>=(const Nullable\<T1\>\&) const method


Determines if the value represented by the current object is greater or equal to the value represented by the specified [Nullable](../) object by applying [operator>=()](./) to these values.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### Return Value

True if the value represented by the current object is greater or equal to the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)