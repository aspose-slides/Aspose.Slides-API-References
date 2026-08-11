---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides برای C++ مرجع API
description: شاخص اولین عنصر را که خارج از بازهٔ مشخص‌شده در یک ReadOnlySpan<T> است پیدا می‌کند
type: docs
weight: 183
url: /fa/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

شاخص اولین عنصری را که خارج از بازهٔ مشخص‌شده در یک ReadOnlySpan<T> است پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### مقدار بازگشت

شاخص صفر مبنا برای اولین عنصری که خارج از بازه است، یا -1 اگر یافت نشود

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) تابع

شاخص اولین عنصری را که خارج از بازهٔ مشخص‌شده در یک Span<T> است پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### مقدار بازگشت

شاخص صفر مبنا برای اولین عنصری که خارج از بازه است، یا -1 اگر یافت نشود

## مراجع

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)