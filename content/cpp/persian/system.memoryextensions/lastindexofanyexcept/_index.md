---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides برای C++ مرجع API
description: آخرین وقوع هر عنصر را به جز سه مقدار مشخص‌شده در یک بازه پیدا می‌کند.
type: docs
weight: 235
url: /fa/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) تابع

آخرین رخداد هر عنصر را به جز سه مقدار مشخص شده در یک بازه پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| value0 | const T\& | اولین مقداری که باید حذف شود |
| value1 | const T\& | دومین مقداری که باید حذف شود |
| value2 | const T\& | سومین مقداری که باید حذف شود |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) تابع

آخرین رخداد هر عنصر را به جز سه مقدار مشخص شده در یک بازه قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| value0 | const T\& | اولین مقداری که باید حذف شود |
| value1 | const T\& | دومین مقداری که باید حذف شود |
| value2 | const T\& | سومین مقداری که باید حذف شود |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

آخرین رخداد هر عنصر را به جز دو مقدار مشخص شده در یک بازه پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| value0 | const T\& | اولین مقداری که باید حذف شود |
| value1 | const T\& | دومین مقداری که باید حذف شود |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) تابع

آخرین رخداد هر عنصر را به جز دو مقدار مشخص شده در یک بازه قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| value0 | const T\& | اولین مقداری که باید حذف شود |
| value1 | const T\& | دومین مقداری که باید حذف شود |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) تابع

آخرین رخداد هر عنصر را به جز یک مقدار مشخص در یک بازه پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| value | const T\& | مقداری که باید حذف شود |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) تابع

آخرین رخداد هر عنصر را به جز یک مقدار مشخص در یک بازه قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| value | const T\& | مقداری که باید حذف شود |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

آخرین رخداد هر عنصر را به جز مقادیر یک دنباله در یک بازه پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دنباله مقادیری که باید حذف شوند |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

آخرین رخداد هر عنصر را به جز مقادیر یک دنباله در یک بازه قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دنباله مقادیری که باید حذف شوند |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) تابع

آخرین رخداد هر عنصر را به جز مقادیر یک دنباله قابل تغییر در یک بازه قابل تغییر پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ای که در آن جستجو می‌شود |
| values | const [Span](../../system/span/)\<T\>\& | دنباله مقادیری که باید حذف شوند |

### مقدار برگشتی

اندیس صفر-پایه عنصر آخر که حذف نشده است، یا -1 اگر پیدا نشود

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)