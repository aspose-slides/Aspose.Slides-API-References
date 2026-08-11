---
title: ComparerAdapter
second_title: مرجع API لـ Aspose.Slides للـ C++
description: محول لاستخدام IComparer داخل بيئة STL. يستخدم IComparer إذا تم تعيينه؛ وإلا يستخدم العامل < (إذا كان متاحًا) أو يُعيد false (إذا لم يكن).
type: docs
weight: 638
url: /ar/system.collections.generic/compareradapter/
---
## ComparerAdapter هيكل

مُحَوِّل لاستخدام [IComparer](../icomparer/) داخل بيئة STL. يستخدم [IComparer](../icomparer/) إذا تم تعيينه؛ وإلا يستخدم العامل < (إن كان متاحًا) أو يُعيد false (إن لم يكن).

```cpp
template<class T>class ComparerAdapter
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T | النوع الجاري مقارنته. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | ينشئ المحول دون وجود أي مُقارن متاح. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | ينشئ المحول. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) وظيفة للأنواع التي يتوفر فيها العامل <. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) وظيفة للأنواع التي لا يتوفر فيها العامل <. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | يضبط كائن المقارن. |

## انظر أيضًا

* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)