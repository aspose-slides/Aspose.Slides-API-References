---
title: TrimStart()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر مشخص‌شده را از ابتدای یک Span تایپ‌شده حذف می‌کند.
type: docs
weight: 391
url: /fa/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) تابع

عنصر مشخص‌شده را از ابتدای یک Span تایپ‌شده حذف می‌کند.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span برای حذف |
| trimElement | const T\& | عنصر برای حذف |

### مقدار بازگشتی

یک Span جدید که عنصر مشخص‌شده از ابتدای آن حذف شده است

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) تابع

عنصر مشخص‌شده را از ابتدای یک Span تایپ‌شدهٔ قابل تغییر حذف می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span قابل تغییر برای حذف |
| trimElement | const T\& | عنصر برای حذف |

### مقدار بازگشتی

یک Span جدید که عنصر مشخص‌شده از ابتدای آن حذف شده است

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

عناصر مشخص‌شده را از ابتدای یک Span تایپ‌شده حذف می‌کند.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span برای حذف |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | عناصر برای حذف |

### مقدار بازگشتی

یک Span جدید که عناصر مشخص‌شده از ابتدای آن حذف شده‌اند

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

عناصر مشخص‌شده را از ابتدای یک Span تایپ‌شدهٔ قابل تغییر حذف می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در Span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span قابل تغییر برای حذف |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | عناصر برای حذف |

### مقدار بازگشتی

یک Span جدید که عناصر مشخص‌شده از ابتدای آن حذف شده‌اند

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) تابع

کاراکترهای فاصله را از ابتدای یک Span کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span کاراکتری برای حذف |

### مقدار بازگشتی

یک Span جدید با حذف کاراکترهای فاصله از ابتدای آن

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) تابع

کاراکترهای فاصله را از ابتدای یک Span کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span کاراکتری قابل تغییر برای حذف |

### مقدار بازگشتی

یک Span جدید با حذف کاراکترهای فاصله از ابتدای آن

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) تابع

کاراکتر مشخص‌شده را از ابتدای یک Span کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span کاراکتری برای حذف |
| trimchar | char16_t | کاراکتر برای حذف |

### مقدار بازگشتی

یک Span جدید که کاراکتر مشخص‌شده از ابتدای آن حذف شده است

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) تابع

کاراکتر مشخص‌شده را از ابتدای یک Span کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span کاراکتری قابل تغییر برای حذف |
| trimchar | char16_t | کاراکتر برای حذف |

### مقدار بازگشتی

یک Span جدید که کاراکتر مشخص‌شده از ابتدای آن حذف شده است

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) تابع

کاراکترهای مشخص‌شده را از ابتدای یک Span کاراکتری حذف می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span کاراکتری برای حذف |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | کاراکترها برای حذف |

### مقدار بازگشتی

یک Span جدید که کاراکترهای مشخص‌شده از ابتدای آن حذف شده‌اند

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) تابع

کاراکترهای مشخص‌شده را از ابتدای یک Span کاراکتری قابل تغییر حذف می‌کند.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Span کاراکتری قابل تغییر برای حذف |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | کاراکترها برای حذف |

### مقدار بازگشتی

یک Span جدید که کاراکترهای مشخص‌شده از ابتدای آن حذف شده‌اند

## مشاهده نیز

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)