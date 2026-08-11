---
title: Overlaps()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند آیا دو ReadOnlySpan در حافظه هم‌پوشانی دارند بدون محاسبه آفست.
type: docs
weight: 274
url: /fa/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


تعیین می‌کند آیا دو ReadOnlySpan در حافظه هم‌پوشانی دارند بدون محاسبه آفست.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در span‌ها |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | اولین span برای بررسی هم‌پوشانی |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دومین span برای بررسی هم‌پوشانی |

### مقدار بازگشت

true اگر spanها هر مکان حافظه‌ای را به‌اشتراک بگذارند، در غیر این صورت false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع


تعیین می‌کند آیا یک [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) در حافظه هم‌پوشانی دارند بدون محاسبه آفست.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در span‌ها |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) برای بررسی هم‌پوشانی |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) برای بررسی هم‌پوشانی |

### مقدار بازگشت

true اگر spanها هر مکان حافظه‌ای را به‌اشتراک بگذارند، در غیر این صورت false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) تابع


تعیین می‌کند آیا دو ReadOnlySpan در حافظه هم‌پوشانی دارند و آفست را محاسبه می‌کند.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در span‌ها |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | اولین span برای بررسی هم‌پوشانی |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دومین span برای بررسی هم‌پوشانی |
| elementOffset | **int32_t**\& | پارامتر خروجی که آفست بین span‌ها را در صورت هم‌پوشانی دریافت می‌کند |

### مقدار بازگشت

true اگر spanها هر مکان حافظه‌ای را به‌اشتراک بگذارند، در غیر این صورت false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) تابع


تعیین می‌کند آیا یک [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) در حافظه هم‌پوشانی دارند و آفست را محاسبه می‌کند.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر در span‌ها |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) برای بررسی هم‌پوشانی |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) برای بررسی هم‌پوشانی |
| elementOffset | **int32_t**\& | پارامتر خروجی که آفست بین span‌ها را در صورت هم‌پوشانی دریافت می‌کند |

### مقدار بازگشت

true اگر spanها هر مکان حافظه‌ای را به‌اشتراک بگذارند، در غیر این صورت false

## مشاهده کنید

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)