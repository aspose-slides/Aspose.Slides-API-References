---
title: LastIndexOfImpl()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يبحث عن الفهرس الأخير لقيمة في نطاق.
type: docs
weight: 14
url: /ar/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function


يبحث عن الفهرس الأخير لقيمة داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) للبحث |
| length | **int32_t** | الطول للبحث ضمنه |
| value | const T\& | القيمة للعثور عليها |

### قيمة الإرجاع

الفهرس الأخير للقيمة، أو -1 إذا لم يتم العثور عليه

## انظر أيضًا

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)