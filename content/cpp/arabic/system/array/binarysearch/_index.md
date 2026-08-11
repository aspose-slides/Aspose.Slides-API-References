---
title: BinarySearch()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يجري بحثًا ثنائيًا في المصفوفة المرتبة.
type: docs
weight: 612
url: /ar/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) طريقة

Performs binary search in the sorted array.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | المصفوفة المرتبة التي يتم البحث فيها |
| item | const T\& | عنصر للبحث عنه |

### قيمة الإرجاع

[Index](../../index/) للعنصر الذي تم البحث عنه إذا تم العثور عليه، وإلا، عدد صحيح سالب هو المكمل الثنائي لمؤشر العنصر التالي الأكبر من العنصر الذي تم البحث عنه أو، إذا لم يكن هناك عنصر أكبر، المكمل الثنائي لعدد العناصر في المصفوفة.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) طريقة

NOT IMPLEMENTED.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Array](../)
* فئة [IComparer](../../../system.collections.generic/icomparer/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)