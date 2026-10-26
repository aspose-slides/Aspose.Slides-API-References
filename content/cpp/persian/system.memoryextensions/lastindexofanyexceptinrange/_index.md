---
title: LastIndexOfAnyExceptInRange()
second_title: مرجع API Aspose.Slides برای C++
description: آخرین رخداد هر عنصری که خارج از بازهٔ مشخص شده درون یک span باشد را پیدا می‌کند.
type: docs
weight: 248
url: /fa/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

آخرین رخداد هر عنصری که خارج از بازه مشخص شده درون یک span باشد را پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو در داخل آن |
| lowInclusive | const T\& | حد پایین بازه (شامل) |
| highInclusive | const T\& | حد بالای بازه (شامل) |

### مقدار بازگشتی

شاخص صفر-پایهٔ آخرین عنصر خارج از بازه، یا -1 اگر یافت نشد

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) تابع

آخرین رخداد هر عنصری که خارج از بازه مشخص شده درون یک span قابل تغییر باشد را پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای جستجو در داخل آن |
| lowInclusive | const T\& | حد پایین بازه (شامل) |
| highInclusive | const T\& | حد بالای بازه (شامل) |

### مقدار بازگشتی

شاخص صفر-پایهٔ آخرین عنصر خارج از بازه، یا -1 اگر یافت نشد

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)