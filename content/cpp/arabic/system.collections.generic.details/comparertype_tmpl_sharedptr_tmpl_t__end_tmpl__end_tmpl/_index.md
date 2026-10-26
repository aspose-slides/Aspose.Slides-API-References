---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides مرجع API لـ C++
description: يقارن العناصر باستخدام منطق 'أصغر'.
type: docs
weight: 157
url: /ar/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > بنية

يقارن العناصر باستخدام منطق 'أصغر'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر المقارنة. |

## الطرق

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | يقارن أنواع المؤشرات التي تنفذ واجهة [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | يقارن أنواع المؤشرات التي لا تنفذ واجهة [IComparable](../../system/icomparable/). |

## انظر أيضًا

* نطاق [System::Collections::Generic::Details](../)
* مكتبة [Aspose.Slides](../../)