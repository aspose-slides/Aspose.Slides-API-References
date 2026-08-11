---
title: operator()()
second_title: مرجع API Aspose.Slides لـ C++
description: يقارن أنواع القيم التي تنفذ الواجهة IComparable.
type: docs
weight: 1
url: /ar/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const طريقة


يقارن أنواع القيم التي تنفذ الواجهة [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Q | النوع للمقارنة. |

### وسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | const Q\& | قيمة الجانب الأيسر. |
| b | const Q\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

True إذا كان **a** يعتبر أصغر من **b**, false otherwise.

## ComparerType::operator()(const Q\&, const Q\&) const طريقة


يقارن الأنواع القيمة الأولية والكائنات التي لا تنفذ الواجهة [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Q | النوع للمقارنة. |

### وسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | const Q\& | قيمة الجانب الأيسر. |
| b | const Q\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

True إذا كان **a** يعتبر أصغر من **b**, false otherwise.

## ComparerType::operator()(const Q\&, const Q\&) const طريقة


يقارن الأنواع ذات النقطة العائمة.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Q | النوع للمقارنة. |

### وسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | const Q\& | قيمة الجانب الأيسر. |
| b | const Q\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

True إذا كان **a** يعتبر أصغر من **b**, false otherwise.

## انظر أيضًا

* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)