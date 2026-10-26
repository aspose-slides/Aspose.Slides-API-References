---
title: CommonPrefixLength()
second_title: Aspose.Slides برای C++ مرجع API
description: طول پیشوند مشترک بین دو بازه را پیدا می‌کند.
type: docs
weight: 27
url: /fa/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


طول پیشوند مشترک بین دو بازه را پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه اول |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه دوم |

### مقدار برگشتی

تعداد عناصر منطبق در ابتدای هر دو بازه

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


طول پیشوند مشترک بین یک بازه قابل تغییر و یک بازه فقط‌خواندنی را پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه فقط‌خواندنی |

### مقدار برگشتی

تعداد عناصر منطبق در ابتدای هر دو بازه

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) تابع


طول پیشوند مشترک بین دو بازه قابل تغییر را پیدا می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر اول |
| other | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر دوم |

### مقدار برگشتی

تعداد عناصر منطبق در ابتدای هر دو بازه

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) تابع


طول پیشوند مشترک بین دو بازه را با استفاده از یک مقایسه‌کنندهٔ برابری سفارشی پیدا می‌کند.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |
| TEqualityComparer | نوع مقایسه‌کنندهٔ برابری |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه اول |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه دوم |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | مقایسه‌کنندهٔ برابری که برای مقایسهٔ عناصر استفاده می‌شود |

### مقدار برگشتی

تعداد عناصر منطبق در ابتدای هر دو بازه

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) تابع


طول پیشوند مشترک بین یک بازه قابل تغییر و یک بازه فقط‌خواندنی را با استفاده از یک مقایسه‌کنندهٔ برابری سفارشی پیدا می‌کند.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |
| TEqualityComparer | نوع مقایسه‌کنندهٔ برابری |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه فقط‌خواندنی |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | مقایسه‌کنندهٔ برابری که برای مقایسهٔ عناصر استفاده می‌شود |

### مقدار برگشتی

تعداد عناصر منطبق در ابتدای هر دو بازه

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) تابع


طول پیشوند مشترک بین دو بازه قابل تغییر را با استفاده از یک مقایسه‌کنندهٔ برابری سفارشی پیدا می‌کند.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه‌ها |
| TEqualityComparer | نوع مقایسه‌کنندهٔ برابری |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر اول |
| other | const [Span](../../system/span/)\<T\>\& | بازه قابل تغییر دوم |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | مقایسه‌کنندهٔ برابری که برای مقایسهٔ عناصر استفاده می‌شود |

### مقدار برگشتی

تعداد عناصر منطبق در ابتدای هر دو بازه

## موارد مرتبط

* Typedef [SharedPtr](../../system/sharedptr/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)