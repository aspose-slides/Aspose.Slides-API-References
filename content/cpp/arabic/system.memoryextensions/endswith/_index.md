---
title: EndsWith()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان ReadOnlySpan<T> ينتهي بقيمة واحدة.
type: docs
weight: 131
url: /ar/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) دالة


يحدد ما إذا كان ReadOnlySpan<T> ينتهي بقيمة واحدة.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في الـ span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للتحقق |
| value | const T\& | القيمة للتحقق منها في نهاية الـ span |

### قيمة الإرجاع

true إذا كان الـ span ينتهي بالقيمة، false وإلا

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة


يحدد ما إذا كان ReadOnlySpan<T> ينتهي بـ ReadOnlySpan<T> آخر

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في الـ spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للتحقق |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للتحقق منه في نهاية الـ span الهدف |

### قيمة الإرجاع

true إذا كان الـ span ينتهي بـ span القيمة، false وإلا

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة


يحدد ما إذا كان Span<T> ينتهي بـ ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في الـ spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | الـ span للتحقق |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للتحقق منه في نهاية الـ span الهدف |

### قيمة الإرجاع

true إذا كان الـ span ينتهي بـ span القيمة، false وإلا

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) دالة


يحدد ما إذا كان ReadOnlySpan<T> ينتهي بـ Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في الـ spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للتحقق |
| value | const [Span](../../system/span/)\<T\>\& | الـ span للتحقق منه في نهاية الـ span الهدف |

### قيمة الإرجاع

true إذا كان الـ span ينتهي بـ span القيمة، false وإلا

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) دالة


يحدد ما إذا كان Span<T> ينتهي بـ Span<T> آخر

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في الـ spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | الـ span للتحقق |
| value | const [Span](../../system/span/)\<T\>\& | الـ span للتحقق منه في نهاية الـ span الهدف |

### قيمة الإرجاع

true إذا كان الـ span ينتهي بـ span القيمة، false وإلا

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) دالة


يحدد ما إذا كان ReadOnlySpan<char16_t> ينتهي بالقيمة المحددة باستخدام StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الـ span للتحقق |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | القيمة للتحقق منها في نهاية الـ span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقارنة السلسلة لاستخدامه |

### قيمة الإرجاع

true إذا كان الـ span ينتهي بالقيمة، false وإلا

## انظر أيضًا

* Enum [StringComparison](../../system/stringcomparison/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* نطاق [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)