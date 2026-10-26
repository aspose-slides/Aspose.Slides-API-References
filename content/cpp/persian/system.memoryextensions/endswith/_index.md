---
title: EndsWith()
second_title: Aspose.Slides برای C++ مرجع API
description: تشخیص می‌دهد آیا یک ReadOnlySpan<T> با یک مقدار تک خاتمه می‌یابد.
type: docs
weight: 131
url: /fa/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) تابع

تشخیص می‌دهد آیا ReadOnlySpan<T> با یک مقدار تک خاتمه می‌یابد.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای بررسی |
| value | const T\& | مقدار برای بررسی در انتهای span |

### مقدار بازگشت

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

تشخیص می‌دهد آیا ReadOnlySpan<T> با یک ReadOnlySpan<T> دیگر خاتمه می‌یابد.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای بررسی |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای بررسی در انتهای span هدف |

### مقدار بازگشت

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

تشخیص می‌دهد آیا Span<T> با یک ReadOnlySpan<T> خاتمه می‌یابد.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای بررسی |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای بررسی در انتهای span هدف |

### مقدار بازگشت

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) تابع

تشخیص می‌دهد آیا ReadOnlySpan<T> با یک Span<T> خاتمه می‌یابد.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span برای بررسی |
| value | const [Span](../../system/span/)\<T\>\& | span برای بررسی در انتهای span هدف |

### مقدار بازگشت

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) تابع

تشخیص می‌دهد آیا Span<T> با یک Span<T> دیگر خاتمه می‌یابد.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای بررسی |
| value | const [Span](../../system/span/)\<T\>\& | span برای بررسی در انتهای span هدف |

### مقدار بازگشت

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) تابع

تشخیص می‌دهد آیا ReadOnlySpan<char16_t> با مقدار مشخص شده به کمک StringComparison خاتمه می‌یابد.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span برای بررسی |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | مقدار برای بررسی در انتهای span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقایسه رشته برای استفاده |

### مقدار بازگشت

true if the span ends with the value, false otherwise

## مراجع

* Enum [StringComparison](../../system/stringcomparison/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)