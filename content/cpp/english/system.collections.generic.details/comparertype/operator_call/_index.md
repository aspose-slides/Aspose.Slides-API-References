---
title: operator()()
second_title: Aspose.Slides for C++ API Reference
description: Compares value types implementing IComparable interface.
type: docs
weight: 1
url: /system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const method


Compares value types implementing [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Return Value

True if **a** is considered less than **b**, false otherwise.

## ComparerType::operator()(const Q\&, const Q\&) const method


Compares primitive value types and objects not implementing [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Return Value

True if **a** is considered less than **b**, false otherwise.

## ComparerType::operator()(const Q\&, const Q\&) const method


Compares floating point types.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Return Value

True if **a** is considered less than **b**, false otherwise.

## See Also

* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)