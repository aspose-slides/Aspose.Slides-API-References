---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides for C++ API Reference
description: Compares elements using 'less' semantics.
type: docs
weight: 157
url: /cpp/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct


Compares elements using 'less' semantics.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Compared elements type. |
## Methods

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compares pointer types implementing [IComparable](../../system/icomparable/) interface. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compares pointer types not implementing [IComparable](../../system/icomparable/) interface. |

## See Also

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)