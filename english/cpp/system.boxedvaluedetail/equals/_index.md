---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: Determines the equality of the specified value using operator==().
type: docs
weight: 1
url: /cpp/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) function


Determines the equality of the specified value using [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the values being compared |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | The first comparand |
| value2 | T | The second comparand |

### Return Value

True if the specified value are equal as determined by [operator==()](../../system/operator_equal_equal/), otherwise - false

## See Also

* Namespace [System::BoxedValueDetail](../)
* Library [Aspose.Slides](../../)
## System::BoxedValueDetail::Equals(T, T) function


Determines the equality of the specified value using method [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the values being compared |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | The first comparand |
| value2 | T | The second comparand |

### Return Value

True if the specified value are equal as determined by method [Equals()](./), otherwise - false

## See Also

* Namespace [System::BoxedValueDetail](../)
* Library [Aspose.Slides](../../)
