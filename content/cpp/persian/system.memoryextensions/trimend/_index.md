---
title: TrimEnd()
second_title: مرجع API Aspose.Slides برای C++
description: عناصر مشخص شده را از انتهای یک Span تایپ‌شده حذف می‌کند.
type: docs
weight: 378
url: /fa/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function

عنصری که مشخص شده است را از انتهای یک Span تایپ‌شده حذف می‌کند.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر موجود در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span برای حذف |
| trimElement | const T\& | عنصری برای حذف |

### مقدار بازگشت

یک Span جدید با عنصر مشخص شده که از انتها حذف شده است

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function

عنصری که مشخص شده است را از انتهای یک Span قابل تغییر حذف می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر موجود در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span قابل تغییر برای حذف |
| trimElement | const T\& | عنصری برای حذف |

### مقدار بازگشت

یک Span جدید با عنصر مشخص شده که از انتها حذف شده است

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

عناصر مشخص شده را از انتهای یک Span تایپ‌شده حذف می‌کند.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر موجود در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span برای حذف |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | عناصر برای حذف |

### مقدار بازگشت

یک Span جدید با عناصر مشخص شده که از انتها حذف شده‌اند

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

عناصر مشخص شده را از انتهای یک Span قابل تغییر حذف می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر موجود در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span قابل تغییر برای حذف |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | عناصر برای حذف |

### مقدار بازگشت

یک Span جدید با عناصر مشخص شده که از انتها حذف شده‌اند

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function

کاراکترهای فضای خالی را از انتهای یک Span کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span کاراکتری برای حذف |

### مقدار بازگشت

یک Span جدید با فضای خالی حذف شده از انتها

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function

کاراکترهای فضای خالی را از انتهای یک Span کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span کاراکتری قابل تغییر برای حذف |

### مقدار بازگشت

یک Span جدید با فضای خالی حذف شده از انتها

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function

کاراکتر مشخص شده را از انتهای یک Span کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span کاراکتری برای حذف |
| trimchar | char16_t | کاراکتر برای حذف |

### مقدار بازگشت

یک Span جدید با کاراکتر مشخص شده که از انتها حذف شده است

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function

کاراکتر مشخص شده را از انتهای یک Span کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span کاراکتری قابل تغییر برای حذف |
| trimchar | char16_t | کاراکتر برای حذف |

### مقدار بازگشت

یک Span جدید با کاراکتر مشخص شده که از انتها حذف شده است

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

کاراکترهای مشخص شده را از انتهای یک Span کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span کاراکتری برای حذف |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | کاراکترها برای حذف |

### مقدار بازگشت

یک Span جدید با کاراکترهای مشخص شده که از انتها حذف شده‌اند

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

کاراکترهای مشخص شده را از انتهای یک Span کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span کاراکتری قابل تغییر برای حذف |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | کاراکترها برای حذف |

### مقدار بازگشت

یک Span جدید با کاراکترهای مشخص شده که از انتها حذف شده‌اند

## مراجع

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)