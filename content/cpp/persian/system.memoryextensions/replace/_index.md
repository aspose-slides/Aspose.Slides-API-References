---
title: Replace()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام رخدادهای یک مقدار را در Span با مقدار جدید جایگزین می‌کند.
type: docs
weight: 287
url: /fa/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) تابع


همهٔ رخدادهای یک مقدار را با مقدار جدید در یک [Span](../../system/span/) جایگزین می‌کند.

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | span برای تغییر در-جا |
| oldValue | const T\& | مقدار برای جستجو و جایگزینی |
| newValue | const T\& | مقدار جدید برای جایگزینی oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) تابع


عناصری را از منبع به مقصد کپی می‌کند و مقادیر مشخص‌شده را در طول کپی جایگزین می‌نماید.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در spans |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | منبع [ReadOnlySpan](../../system/readonlyspan/) برای کپی |
| destination | [Span](../../system/span/)\<T\>\& | مقصد [Span](../../system/span/) برای کپی |
| oldValue | const T\& | مقدار برای جستجو و جایگزینی در هنگام کپی |
| newValue | const T\& | مقدار جدید برای جایگزینی oldValue |

## موارد مرتبط

* کلاس [Span](../../system/span/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* فضای نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)