---
title: Trim()
second_title: Aspose.Slides برای C++ مرجع API
description: عنصر مشخص را از هر دو سر یک بازهٔ تایپ‌شده حذف می‌کند.
type: docs
weight: 365
url: /fa/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) تابع


عنصری مشخص را از هر دو طرف یک بازهٔ تایپ‌شده حذف می‌کند.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | T | The element to trim |

### مقدار بازگشتی

A new span with the specified element trimmed from both ends

## System::MemoryExtensions::Trim(Span\<T\>\&, T) تابع


عنصری مشخص را از هر دو طرف یک بازهٔ تایپ‌شده قابل تغییر حذف می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | T | The element to trim |

### مقدار بازگشتی

A new span with the specified element trimmed from both ends

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


عناصر مشخص را از هر دو طرف یک بازهٔ تایپ‌شده حذف می‌کند.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### مقدار بازگشتی

A new span with the specified elements trimmed from both ends

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


عناصر مشخص را از هر دو طرف یک بازهٔ تایپ‌شده قابل تغییر حذف می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | The type of elements in the span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### مقدار بازگشتی

A new span with the specified elements trimmed from both ends

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) تابع


کاراکترهای فضای سفید را از هر دو طرف یک بازهٔ کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |

### مقدار بازگشتی

A new span with whitespace trimmed from both ends

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) تابع


کاراکترهای فضای سفید را از هر دو طرف یک بازهٔ کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |

### مقدار بازگشتی

A new span with whitespace trimmed from both ends

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)