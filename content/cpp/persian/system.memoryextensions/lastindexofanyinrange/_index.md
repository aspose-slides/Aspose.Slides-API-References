---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides برای C++ مرجع API
description: آخرین وقوع هر عنصر در بازه‌ی مشخص‌شده را در یک span پیدا می‌کند.
type: docs
weight: 261
url: /fa/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

آخرین وقوع هر عنصر در بازهٔ مشخص‌شده را در یک span پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### مقدار بازگشتی

The zero-based index of the last element within the range, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) تابع

آخرین وقوع هر عنصر در بازهٔ مشخص‌شده را در یک span قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### مقدار بازگشتی

The zero-based index of the last element within the range, or -1 if not found

## مراجع

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)