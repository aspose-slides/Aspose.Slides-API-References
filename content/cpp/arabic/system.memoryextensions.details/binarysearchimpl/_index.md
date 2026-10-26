---
title: BinarySearchImpl()
second_title: Aspose.Slides لـ C++ مرجع API
description: تنفيذ البحث الثنائي الشائع.
type: docs
weight: 118
url: /ar/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) دالة

تنفيذ البحث الثنائي الشائع.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |
| TValue | نوع القيمة المراد البحث عنها |
| TCompareFunc | نوع الدالة للمقارنة |

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى للبحث |
| value | const TValue\& | القيمة المراد البحث عنها |
| compareFunc | TCompareFunc | دالة تقارن القيمة مع عنصر المدى وتعيد **int32_t** (-1, 0, 1) |

### قيمة الإرجاع

[Index](../../system/index/) للعنصر الموجود أو المكمل الثنائي لنقطة الإدراج

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* النطاق [System::MemoryExtensions::Details](../)
* المكتبة [Aspose.Slides](../../)