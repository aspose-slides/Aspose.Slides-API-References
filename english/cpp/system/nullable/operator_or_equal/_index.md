---
title: operator|=()
second_title: Aspose.Slides for C++ API Reference
description: Applies operator|=() to the value represented by the current object using the specified value as a right-side argument.
type: docs
weight: 248
url: /cpp/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) method


Applies [operator|=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The template parameter to make SFINAE work. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | **bool** | A boolean value that is used as a right-side value of the [operator|=()](./) applied to the value represented by the current object. |

### Return Value

A reference to the self.

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)