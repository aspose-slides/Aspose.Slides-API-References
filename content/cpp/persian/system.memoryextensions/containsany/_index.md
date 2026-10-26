---
title: ContainsAny()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا یک span فقط‌خواندنی شامل هر یک از دو مقدار باشد.
type: docs
weight: 53
url: /fa/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک span فقط‌خواندنی شامل هر یک از دو مقدار باشد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| value0 | const T\& | اولین مقدار برای جستجو |
| value1 | const T\& | دومین مقدار برای جستجو |

### مقدار بازگشت

true اگر هر یک از مقادیر در span یافت شود، در غیر این صورت false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) تابع


بررسی می‌کند که آیا یک span فقط‌خواندنی شامل هر یک از سه مقدار باشد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| value0 | const T\& | اولین مقدار برای جستجو |
| value1 | const T\& | دومین مقدار برای جستجو |
| value2 | const T\& | سومین مقدار برای جستجو |

### مقدار بازگشت

true اگر هر یک از مقادیر در span یافت شود، در غیر این صورت false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) تابع


بررسی می‌کند که آیا یک span قابل‌تغییر شامل هر یک از دو مقدار باشد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span قابل‌تغییر برای جستجو |
| value0 | const T\& | اولین مقدار برای جستجو |
| value1 | const T\& | دومین مقدار برای جستجو |

### مقدار بازگشت

true اگر هر یک از مقادیر در span یافت شود، در غیر این‌صورت false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) تابع


بررسی می‌کند که آیا یک span قابل‌تغییر شامل هر یک از سه مقدار باشد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span قابل‌تغییر برای جستجو |
| value0 | const T\& | اولین مقدار برای جستجو |
| value1 | const T\& | دومین مقدار برای جستجو |
| value2 | const T\& | سومین مقدار برای جستجو |

### مقدار بازگشت

true اگر هر یک از مقادیر در span یافت شود، در غیر این‌صورت false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


بررسی می‌کند که آیا یک span فقط‌خواندنی شامل هر مقدار از یک span دیگر باشد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spanها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span مقادیر برای جستجو |

### مقدار بازگشت

true اگر هر مقدار از values در span یافت شود، در غیر این‌صورت false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


بررسی می‌کند که آیا یک span قابل‌تغییر شامل هر مقدار از یک span فقط‌خواندنی باشد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spanها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span قابل‌تغییر برای جستجو |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span فقط‌خواندنی مقادیر برای جستجو |

### مقدار بازگشت

true اگر هر مقدار از values در span یافت شود، در غیر این‌صورت false

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)