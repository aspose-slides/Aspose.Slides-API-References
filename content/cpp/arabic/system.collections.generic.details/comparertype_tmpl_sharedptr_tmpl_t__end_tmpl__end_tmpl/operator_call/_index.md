---
title: operator()()
second_title: مرجع API Aspose.Slides للغة C++
description: يقارن أنواع المؤشرات التي تنفذ الواجهة IComparable.
type: docs
weight: 1
url: /ar/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

يقارن أنواع المؤشرات التي تنفذ واجهة [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| Q | النوع للمقارنة. |

### الحجج

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | قيمة الطرف الأيسر. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

صحيح إذا اعتُبر **a** أصغر من **b**، وإلا خطأ.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

يقارن أنواع المؤشرات التي لا تنفذ واجهة [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| Q | النوع للمقارنة. |

### الحجج

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | قيمة الطرف الأيسر. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

صحيح إذا اعتُبر **a** أصغر من **b**، وإلا خطأ.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)