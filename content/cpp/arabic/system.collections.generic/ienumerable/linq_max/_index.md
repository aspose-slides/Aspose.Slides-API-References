---
title: LINQ_Max()
second_title: مرجع API Aspose.Slides للـ C++
description: تستدعي دالة تحويل على كل عنصر في تسلسل عام وتعيد القيمة القصوى الناتجة.
type: docs
weight: 352
url: /ar/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) طريقة

يستدعي دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ResultType | نوع القيمة التي تُعيدها الدالة المحددة. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | دالة تحويل لتطبيقها على كل عنصر. |

### قيمة الإرجاع

القيمة القصوى في التسلسل.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) طريقة

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## انظر أيضًا

* الفئة [Func](../../../system/func/)
* الفئة [IEnumerable](../)
* النطاق [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)