---
title: IndexOfAnyInRange()
second_title: Aspose.Slides برای مرجع API C++
description: شاخص اولین عنصری که در بازهٔ مشخص‌شده در یک ReadOnlySpan<T> قرار دارد را پیدا می‌کند
type: docs
weight: 196
url: /fa/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

شاخص اولین عنصری که در بازه مشخص‌شده در یک ReadOnlySpan<T> قرار دارد را پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span برای جستجو |
| lowInclusive | const T\& | حد پایین بازه (شامل) |
| highInclusive | const T\& | حد بالای بازه (شامل) |

### مقدار بازگشت

شاخص صفر-محور اولین عنصری که در بازه قرار دارد، یا -1 اگر یافت نشود

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) تابع

شاخص اولین عنصری که در بازه مشخص‌شده در یک Span<T> قرار دارد را پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span برای جستجو |
| lowInclusive | const T\& | حد پایین بازه (شامل) |
| highInclusive | const T\& | حد بالای بازه (شامل) |

### مقدار بازگشت

شاخص صفر-محور اولین عنصری که در بازه قرار دارد، یا -1 اگر یافت نشود

## مراجع

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)