---
title: operator()()
second_title: Aspose.Slides for C++ API Reference
description: Comparison function for types with operator < available.
type: docs
weight: 27
url: /cpp/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) function for types with operator < available.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Return Value

True if **x** is considered less than **y**, false otherwise.

## See Also

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) function for types with operator < not available.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Return Value

True if comparator is set and **x** is considered less than **y**, false otherwise.

## See Also

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
