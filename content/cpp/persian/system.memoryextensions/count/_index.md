---
title: Count()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد وقوع یک مقدار در یک بازه فقط‌خواندنی را شمارش می‌کند.
type: docs
weight: 118
url: /fa/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) function

تعداد وقوع یک مقدار در یک بخش فقط‌خواندنی را شمارش می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| value | const T\& | value برای شمارش |

### مقدار برگشتی

تعداد دفعاتی که value در span ظاهر می‌شود

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

تعداد وقوع یک بخش در یک بخش فقط‌خواندنی دیگر را شمارش می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای شمارش وقوع‌ها |

### مقدار برگشتی

تعداد دفعاتی که value در span ظاهر می‌شود

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) function

تعداد وقوع یک مقدار منفرد در یک Span<T> را شمارش می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای جستجو |
| value | const T\& | value برای شمارش وقوع‌ها |

### مقدار برگشتی

تعداد وقوع‌های value در span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

تعداد وقوع یک ReadOnlySpan<T> در یک Span<T> را شمارش می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای جستجو |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span حاوی مقادیر برای شمارش وقوع‌ها |

### مقدار برگشتی

تعداد وقوع‌های value span در target span

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضا‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)