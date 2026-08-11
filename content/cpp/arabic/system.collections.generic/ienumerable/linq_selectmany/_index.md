---
title: LINQ_SelectMany()
second_title: مرجع API Aspose.Slides للـ C++
description: ينفّذ العملية على كل عنصر من تسلسل ويجمع التسلسلات الناتجة في تسلسل واحد.
type: docs
weight: 300
url: /ar/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

ينفّذ العملية على كل عنصر من تسلسل ويجمع التسلسلات الناتجة في تسلسل واحد.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ResultType | النوع الذي تُرجعه **selector**. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | دالة تحويل. |

### قيمة الإرجاع

كائن [IEnumerable](../) يحتوي على نتيجة استدعاء دالة إسقاط من-إلى-متعدد على كل عنصر من تسلسل الإدخال.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IEnumerable](../)
* فئة [Func](../../../system/func/)
* مساحة اسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)