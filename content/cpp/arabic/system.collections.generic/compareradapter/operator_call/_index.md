---
title: operator()()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: دالة مقارنة للأنواع التي يتوفر فيها العامل <.
type: docs
weight: 27
url: /ar/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const method

[Comparison](../../../system/comparison/) دالة للأنواع التي يتوفر فيها العامل <.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| Q | النوع الذي يتم مقارنته؛ قالب لتوافر تحويل النوع. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const Q\& | القيمة الأولى للمقارنة. |
| y | const Q\& | القيمة الثانية للمقارنة. |

### قيمة الإرجاع

صحيح إذا كان **x** يعتبر أصغر من **y**، وإلا خطأ.

## ComparerAdapter::operator()(const Q\&, const Q\&) const method

[Comparison](../../../system/comparison/) دالة للأنواع التي لا يتوفر فيها العامل <.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| Q | النوع الذي يتم مقارنته؛ قالب لتوافر تحويل النوع. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const Q\& | القيمة الأولى للمقارنة. |
| y | const Q\& | القيمة الثانية للمقارنة. |

### قيمة الإرجاع

صحيح إذا كان المقارن مضبوطًا و **x** يعتبر أصغر من **y**، وإلا خطأ.

## انظر أيضًا

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)