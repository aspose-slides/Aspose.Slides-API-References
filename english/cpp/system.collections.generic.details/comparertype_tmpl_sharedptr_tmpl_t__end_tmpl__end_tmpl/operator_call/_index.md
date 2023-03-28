---
title: operator()()
second_title: Aspose.Slides for C++ API Reference
description: Compares pointer types implementing IComparable interface.
type: docs
weight: 1
url: /cpp/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\&) const method


Compares pointer types implementing [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS value. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS value. |

### Return Value

True if **a** is considered less than **b**, false otherwise.

## See Also

* Class [IComparable](../../../system/icomparable/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)
## ComparerType< SharedPtr< T > >::operator()(const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\&) const method


Compares pointer types not implementing [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS value. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS value. |

### Return Value

True if **a** is considered less than **b**, false otherwise.

## See Also

* Class [IComparable](../../../system/icomparable/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)
