---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the value represented by the current object is equal to the value represented by the specified Nullable object.
type: docs
weight: 118
url: /cpp/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const method


Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the [Nullable](../) object to compare with |

### Return Value

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)