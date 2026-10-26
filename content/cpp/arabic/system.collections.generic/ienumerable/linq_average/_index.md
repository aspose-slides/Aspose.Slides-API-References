---
title: LINQ_Average()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحسب متوسط تسلسل من القيم الرقمية.
type: docs
weight: 365
url: /ar/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() طريقة

يحسب المتوسط لمجموعة من القيم الرقمية.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### قيمة الإرجاع

متوسط القيم في المجموعة.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) طريقة

يحسب المتوسط لمجموعة من القيم التي يتم الحصول عليها عن طريق استدعاء دالة تحويل على كل عنصر في مجموعة الإدخال.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ResultType | نوع القيمة التي تُرجِعها الدالة selector. |

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | دالة تحويل لتطبيقها على كل عنصر. |

### قيمة الإرجاع

متوسط القيم المتوقعة.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) طريقة

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## انظر أيضًا

* الفئة [IEnumerable](../)
* الفئة [Func](../../../system/func/)
* النطاق [System::Collections::Generic](../../)
* المكتبة [Aspose.Slides](../../../)