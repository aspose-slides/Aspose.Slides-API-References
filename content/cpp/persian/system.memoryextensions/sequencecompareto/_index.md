---
title: SequenceCompareTo()
second_title: مرجع API Aspose.Slides برای C++
description: دو ReadOnlySpan را به صورت لغت‌نامه‌ای مقایسه می‌کند.
type: docs
weight: 313
url: /fa/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

دو ReadOnlySpan را به صورت لغت‌نامه‌ای مقایسه می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### مقدار بازگشت

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

یک [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) را به صورت لغت‌نامه‌ای مقایسه می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |

### مقدار بازگشت

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) تابع

یک [ReadOnlySpan](../../system/readonlyspan/) و [Span](../../system/span/) را به صورت لغت‌نامه‌ای مقایسه می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |
| other | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |

### مقدار بازگشت

- 1 if span < other, 0 if span == other, 1 if span > other

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)