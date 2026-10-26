---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides برای ارجاع API C++
description: بررسی می‌کند که آیا یک span فقط-خواندنی شامل عنصری خارج از بازهٔ مشخص‌شده است یا نه.
type: docs
weight: 79
url: /fa/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک span فقط-خواندنی شامل عنصری خارج از بازهٔ مشخص‌شده است یا نه.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span (باید قابل مقایسه باشد) |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| lowInclusive | const T\& | حد پایین (شامل) |
| highInclusive | const T\& | حد بالا (شامل) |

### مقدار بازگشتی

در صورت یافتن هر عنصر خارج از بازه true و در غیر این صورت false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک span قابل تغییر شامل عنصری خارج از بازهٔ مشخص‌شده است یا نه.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span (باید قابل مقایسه باشد) |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span قابل تغییر برای جستجو |
| lowInclusive | const T\& | حد پایین (شامل) |
| highInclusive | const T\& | حد بالا (شامل) |

### مقدار بازگشتی

در صورت یافتن هر عنصر خارج از بازه true و در غیر این صورت false

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)