---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides for C++ API 参考
description: 使用‘less’语义比较元素。
type: docs
weight: 157
url: /zh/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

比较元素使用“less”语义。

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被比较的元素类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | 比较实现 [IComparable](../../system/icomparable/) 接口的指针类型。 |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | 比较未实现 [IComparable](../../system/icomparable/) 接口的指针类型。 |

## 另见

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)