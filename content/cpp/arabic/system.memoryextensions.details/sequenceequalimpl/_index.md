---
title: SequenceEqualImpl()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتحقق مما إذا كان نطاقان متساويان بدءًا من المواضع المحددة.
type: docs
weight: 27
url: /ar/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) دالة

يتحقق مما إذا كان مجالان متساويان بدءًا من المواضع المحددة.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المجالات |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المجال الأول |
| start | const **int32_t** | الفهرس الابتدائي في المجال الأول |
| length | **int32_t** | عدد العناصر للمقارنة |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المجال الثاني |

### قيمة الإرجاع

صحيح إذا كانت النطاقات المحددة متساوية، خطأ وإلا

## أنظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* النطاق [System::MemoryExtensions::Details](../)
* المكتبة [Aspose.Slides](../../)