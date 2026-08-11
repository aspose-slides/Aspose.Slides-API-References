---
title: Overlaps()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كان اثنان من ReadOnlySpans يتداخلان في الذاكرة دون حساب الإزاحة.
type: docs
weight: 274
url: /ar/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يحدد ما إذا كان اثنان من ReadOnlySpans يتداخلان في الذاكرة دون حساب الإزاحة.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | أول span للتحقق من التداخل |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ثاني span للتحقق من التداخل |

### قيمة الإرجاع

صحيح إذا كانت الـ spans تشترك في أي مواقع ذاكرة مشتركة، وإلا خطأ

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يحدد ما إذا كان [Span](../../system/span/) و[ReadOnlySpan](../../system/readonlyspan/) يتداخلان في الذاكرة دون حساب الإزاحة.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | ال[Span](../../system/span/) للتحقق من التداخل |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ال[ReadOnlySpan](../../system/readonlyspan/) للتحقق من التداخل |

### قيمة الإرجاع

صحيح إذا كانت الـ spans تشترك في أي مواقع ذاكرة مشتركة، وإلا خطأ

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) دالة

يحدد ما إذا كان اثنان من ReadOnlySpans يتداخلان في الذاكرة ويحساب الإزاحة.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | أول span للتحقق من التداخل |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ثاني span للتحقق من التداخل |
| elementOffset | **int32_t**\& | معلمة إخراج تستقبل الإزاحة بين الـ spans إذا تداخلت |

### قيمة الإرجاع

صحيح إذا كانت الـ spans تشترك في أي مواقع ذاكرة مشتركة، وإلا خطأ

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) دالة

يحدد ما إذا كان [Span](../../system/span/) و[ReadOnlySpan](../../system/readonlyspan/) يتداخلان في الذاكرة ويحساب الإزاحة.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | ال[Span](../../system/span/) للتحقق من التداخل |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ[ReadOnlySpan](../../system/readonlyspan/) للتحقق من التداخل |
| elementOffset | **int32_t**\& | معلمة إخراج تستقبل الإزاحة بين الـ spans إذا تداخلت |

### قيمة الإرجاع

صحيح إذا كانت الـ spans تشترك في أي مواقع ذاكرة مشتركة، وإلا خطأ

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)