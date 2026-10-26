---
title: IndexOf()
second_title: Aspose.Slides برای C++ مرجع API
description: موقعیت یک مقدار ReadOnlySpan<T> را در ReadOnlySpan<T> دیگری پیدا می‌کند
type: docs
weight: 144
url: /fa/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

موقعیت یک مقدار ReadOnlySpan<T> را در ReadOnlySpan<T> دیگر پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### مقدار بازگشتی

اندیس صفر-مبنا برای اولین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) تابع

موقعیت یک مقدار واحد را در ReadOnlySpan<T> پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### مقدار بازگشتی

اندیس صفر-مبنا برای اولین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

موقعیت یک مقدار ReadOnlySpan<T> را در Span<T> پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### مقدار بازگشتی

اندیس صفر-مبنا برای اولین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) تابع

موقعیت یک مقدار واحد را در Span<T> پیدا می‌کند

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### مقدار بازگشتی

اندیس صفر-مبنا برای اولین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) تابع

موقعیت یک مقدار ReadOnlySpan<char16_t> را در ReadOnlySpan<char16_t> با استفاده از StringComparison پیدا می‌کند.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### مقدار بازگشتی

اندیس صفر-مبنا برای اولین رخداد، یا -1 در صورت عدم یافتن

## موارد مرتبط

* Enum [StringComparison](../../system/stringcomparison/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* نام‌فضا [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)