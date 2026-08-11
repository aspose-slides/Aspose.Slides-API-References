---
title: LastIndexOfAny()
second_title: مرجع API Aspose.Slides برای C++
description: آخرین رخداد هر یک از سه مقدار مشخص شده را درون یک بازه پیدا می‌کند.
type: docs
weight: 222
url: /fa/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\>) تابع

آخرین رخداد هر یک از سه مقدار مشخص شده را درون یک بازه (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که جستجو می‌شود |
| value1 | const T\& | دومین مقداری که جستجو می‌شود |
| value2 | const T\& | سومین مقداری که جستجو می‌شود |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\>) تابع

آخرین رخداد هر یک از سه مقدار مشخص شده را درون یک بازه قابل تغییر (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که جستجو می‌شود |
| value1 | const T\& | دومین مقداری که جستجو می‌شود |
| value2 | const T\& | سومین مقداری که جستجو می‌شود |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

آخرین رخداد هر یک از دو مقدار مشخص شده را درون یک بازه (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که جستجو می‌شود |
| value1 | const T\& | دومین مقداری که جستجو می‌شود |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) تابع

آخرین رخداد هر یک از دو مقدار مشخص شده را درون یک بازه قابل تغییر (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که جستجو می‌شود |
| value1 | const T\& | دومین مقداری که جستجو می‌شود |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

آخرین رخداد هر مقداری از یک دنباله را درون یک بازه (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دنباله‌ای از مقادیر برای جستجو |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

آخرین رخداد هر مقداری از یک دنباله را درون یک بازه قابل تغییر (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دنباله‌ای از مقادیر برای جستجو |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) تابع

آخرین رخداد هر مقداری از یک دنباله قابل تغییر را درون یک بازه قابل تغییر (span) پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| values | const [Span](../../system/span/)\<T\>\& | دنباله‌ای از مقادیر برای جستجو |

### مقدار بازگشت

اندیس صفر-مبنا برای آخرین رخداد، یا -1 در صورت عدم یافتن

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)