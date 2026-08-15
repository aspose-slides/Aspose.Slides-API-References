---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides for C++ API 參考
description: 使用「less」語意比較元素。
type: docs
weight: 157
url: /zh-hant/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

比較元素使用「less」語意。

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | 被比較的元素類型。 |
## 方法

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | 比較實作 [IComparable](../../system/icomparable/) 介面的指標類型。 |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | 比較未實作 [IComparable](../../system/icomparable/) 介面的指標類型。 |

## 另請參閱

* 命名空間 [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)