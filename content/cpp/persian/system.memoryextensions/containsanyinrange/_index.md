---
title: ContainsAnyInRange()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا یک بازه فقط-خواندنی شامل هر عنصری در محدوده مشخص شده است یا خیر.
type: docs
weight: 92
url: /fa/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه‌ی فقط-خواندنی شامل هر عنصری در محدوده‌ی مشخص شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه (باید قابل مقایسه باشد) |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| lowInclusive | const T\& | حد پایین (شامل) |
| highInclusive | const T\& | حد بالا (شامل) |

### مقدار بازگشتی

true اگر هر عنصری در محدوده یافت شود، false در غیر این صورت

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه‌ی قابل تغییر شامل هر عنصری در محدوده‌ی مشخص شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه (باید قابل مقایسه باشد) |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ی قابل تغییر که جستجو در آن انجام می‌شود |
| lowInclusive | const T\& | حد پایین (شامل) |
| highInclusive | const T\& | حد بالا (شامل) |

### مقدار بازگشتی

true اگر هر عنصری در محدوده یافت شود، false در غیر این صورت

## مراجع

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)