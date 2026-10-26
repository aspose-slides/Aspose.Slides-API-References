---
title: LastIndexOf()
second_title: مرجع API Aspose.Slides برای C++
description: آخرین رخداد یک دنباله را درون یک span پیدا می‌کند.
type: docs
weight: 209
url: /fa/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

آخرین رخداد یک دنباله را درون یک span پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### مقدار بازگشتی

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

آخرین رخداد یک مقدار تک را درون یک span پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### مقدار بازگشتی

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

آخرین رخداد یک دنباله را درون یک span قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### مقدار بازگشتی

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

آخرین رخداد یک مقدار تک را درون یک span قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### مقدار بازگشتی

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

آخرین رخداد یک مقدار را درون یک span با استفاده از مقایسه رشته‌ای مشخص شده پیدا می‌کند.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### مقدار بازگشتی

The zero-based index of the last occurrence, or -1 if not found

## موارد مرتبط

* Enum [StringComparison](../../system/stringcomparison/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)