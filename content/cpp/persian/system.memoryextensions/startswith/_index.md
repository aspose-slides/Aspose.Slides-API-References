---
title: StartsWith()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا بازه با مقدار مشخص شروع می‌شود.
type: docs
weight: 352
url: /fa/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) تابع

بررسی می‌کند که آیا بازه با مقدار مشخص شروع می‌شود.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که باید بررسی شود |
| value | const T\& | مقداری که باید در ابتدای بازه بررسی شود |

### مقدار بازگشت

true اگر بازه با مقدار شروع شود، در غیر این صورت false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

بررسی می‌کند که آیا بازه با بازه مقدار مشخص شروع می‌شود.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که باید بررسی شود |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که شامل مقادیر برای بررسی در ابتدای بازه است |

### مقدار بازگشت

true اگر بازه با بازه مقدار شروع شود، در غیر این صورت false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

بررسی می‌کند که آیا بازه قابل تغییر با بازه مقدار فقط-خواندنی مشخص شروع می‌شود.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر که باید بررسی شود |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه فقط-خواندنی که شامل مقادیر برای بررسی است |

### مقدار بازگشت

true اگر بازه با بازه مقدار شروع شود، در غیر این صورت false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) تابع

بررسی می‌کند که آیا بازه فقط-خواندنی با بازه مقدار قابل تغییر مشخص شروع می‌شود.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه فقط-خواندنی که باید بررسی شود |
| value | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر که شامل مقادیر برای بررسی است |

### مقدار بازگشت

true اگر بازه با بازه مقدار شروع شود، در غیر این صورت false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) تابع

بررسی می‌کند که آیا بازهٔ کاراکتری با بازهٔ مقدار مشخص با استفاده از StringComparison شروع می‌شود.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | بازهٔ کاراکتری که باید بررسی شود |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | بازهٔ کاراکتری که شامل مقادیر برای بررسی است |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقایسهٔ رشته‌ای برای انجام |

### مقدار بازگشت

true اگر بازه با بازه مقدار شروع شود، در غیر این صورت false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) تابع

بررسی می‌کند که آیا بازهٔ رشته‌ای با آرایهٔ کاراکتری مشخص شروع می‌شود.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | بازهٔ رشته‌ای که باید بررسی شود |
| val | const char16_t * | آرایهٔ کاراکتری که باید در ابتدای بازه بررسی شود |

### مقدار بازگشت

true اگر بازه با آرایهٔ کاراکتری شروع شود، در غیر این صورت false

## مراجع دیگر

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)