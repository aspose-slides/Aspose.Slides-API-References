---
title: operator==()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the value represented by the current object is null.
type: docs
weight: 105
url: /cpp/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const method


Determines if the value represented by the current object is null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Return Value

True if the value represented by the current object is null, otherwise - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Nullable::operator==(const T1\&) const method


Determines if the value represented by the current object is equal to the specified value.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### Return Value

True if the value represented by the current object is equal to the specified value, otherwise - false

## See Also

* Struct [IsNullable](../../isnullable/)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Nullable::operator==(const [Nullable](../)\<T1\>\&) const method


Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
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

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
