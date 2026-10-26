---
title: LINQ_Min()
second_title: مرجع API Aspose.Slides للغة C++
description: تستدعي دالة تحويل على كل عنصر من تسلسل عام وتعيد القيمة الصغرى الناتجة.
type: docs
weight: 339
url: /ar/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


يقوم باستدعاء وظيفة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الصغرى الناتجة.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ResultType | نوع القيمة التي يُرجعها selector. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | دالة تحويل لتطبيقها على كل عنصر. |

### قيمة الإرجاع

القيمة الصغرى في التسلسل.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## انظر أيضا

* الفئة [Func](../../../system/func/)
* الفئة [IEnumerable](../)
* النطاق [System::Collections::Generic](../../)
* المكتبة [Aspose.Slides](../../../)