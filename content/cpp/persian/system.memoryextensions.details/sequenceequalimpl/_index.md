---
title: SequenceEqualImpl()
second_title: Aspose.Slides برای مرجع API C++
description: بررسی می‌کند که آیا دو spans از موقعیت‌های مشخص‌شده برابر هستند.
type: docs
weight: 27
url: /fa/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) تابع

بررسی می‌کند که آیا دو Span از موقعیت‌های مشخص‌شده برابر هستند یا نه.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در Span‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span اول |
| start | const **int32_t** | اندیس شروع در Span اول |
| length | **int32_t** | تعداد عناصری که باید مقایسه شوند |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span دوم |

### مقدار برگشتی

در صورتی که بازه‌های مشخص شده برابر باشند true و در غیر این صورت false

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* فضای نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)