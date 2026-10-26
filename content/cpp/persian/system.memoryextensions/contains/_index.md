---
title: Contains()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا یک ReadOnlySpan شامل مقدار خاصی است یا خیر.
type: docs
weight: 40
url: /fa/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) تابع

بررسی می‌کند که آیا یک ‎ReadOnlySpan‎ شامل مقدار خاصی است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای جستجو |
| value | const T\& | مقدار برای جستجو |

### مقدار بازگشت

true اگر مقدار در span یافت شود، false در غیر این صورت

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) تابع

بررسی می‌کند که آیا یک ‎Span‎ قابل تغییر شامل مقدار خاصی است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای جستجو |
| value | const T\& | مقدار برای جستجو |

### مقدار بازگشت

true اگر مقدار در span یافت شود، false در غیر این صورت

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) تابع

بررسی می‌کند که آیا یک ‎ReadOnlySpan<char16_t>‎ شامل یک ‎ReadOnlySpan<char16_t>‎ دیگر با قوانین مقایسهٔ مشخص است یا خیر.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span برای جستجو |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span برای جستجو |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقایسهٔ رشته برای انجام |

### مقدار بازگشت

true اگر مقدار در span یافت شود، false در غیر این صورت

## موارد مرتبط

* enum [StringComparison](../../system/stringcomparison/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)