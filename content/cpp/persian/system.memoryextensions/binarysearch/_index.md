---
title: BinarySearch()
second_title: مرجع API Aspose.Slides برای C++
description: جستجوی دودویی را بر روی یک بازه‌ی مرتب انجام می‌دهد.
type: docs
weight: 14
url: /fa/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) تابع

جستجوی دودویی را بر روی یک بازه‌ی مرتب انجام می‌دهد.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |
| TComparable | نوع مقدار مقایسه‌پذیر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ی مرتب برای جستجو |
| comparable | const TComparable\& | مقداری که باید جستجو شود |

### مقدار بازگشت

[Index](../../system/index/) عنصر پیدا شده، یا مکمل بیت‌وار نقطه‌ی درج اگر یافت نشد

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) تابع

جستجوی دودویی را بر روی یک بازه‌ی مرتب با استفاده از مقایسه‌گر سفارشی انجام می‌دهد.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |
| TComparer | نوع مقایسه‌گر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ی مرتب برای جستجو |
| value | const T\& | مقداری که باید جستجو شود |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | مقایسه‌گری که برای مقایسه‌ها استفاده می‌شود |

### مقدار بازگشت

[Index](../../system/index/) عنصر پیدا شده، یا مکمل بیت‌وار نقطه‌ی درج اگر یافت نشد

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) تابع

جستجوی دودویی را بر روی یک بازه‌ی مرتب قابل تغییر انجام می‌دهد.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |
| TComparable | نوع مقدار مقایسه‌پذیر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ی مرتب برای جستجو |
| comparable | const TComparable\& | مقداری که باید جستجو شود |

### مقدار بازگشت

[Index](../../system/index/) عنصر پیدا شده، یا مکمل بیت‌وار نقطه‌ی درج اگر یافت نشد

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) تابع

جستجوی دودویی را بر روی یک بازه‌ی مرتب قابل تغییر با استفاده از مقایسه‌گر سفارشی انجام می‌دهد.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |
| TComparer | نوع مقایسه‌گر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه‌ی مرتب برای جستجو |
| value | const T\& | مقداری که باید جستجو شود |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | مقایسه‌گری که برای مقایسه‌ها استفاده می‌شود |

### مقدار بازگشت

[Index](../../system/index/) عنصر پیدا شده، یا مکمل بیت‌وار نقطه‌ی درج اگر یافت نشد

## همچنین ببینید

* Typedef [SharedPtr](../../system/sharedptr/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)