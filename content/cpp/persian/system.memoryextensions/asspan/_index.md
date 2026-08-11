---
title: AsSpan()
second_title: مرجع API Aspose.Slides برای C++
description: یک بازه (span) از یک آرایه ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) تابع

یک بازه (span) از یک آرایه ایجاد می‌کند.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع عناصر موجود در آرایه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | آرایه منبع. |
| start | **int32_t** | اندیس شروع در آرایه. |
| length | **int32_t** | طول بازه. |

### مقدار بازگشت

Span<T> که بخش مشخصی از آرایه را در بر می‌گیرد.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) تابع

یک بازه فقط-خواندنی (read-only span) از یک رشته ایجاد می‌کند.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | رشته منبع. |
| start | **int32_t** | اندیس شروع در رشته. |
| length | **int32_t** | طول بازه. |

### مقدار بازگشت

ReadOnlySpan<char16_t> که بخش مشخصی از رشته را در بر می‌گیرد.

## موارد مرتبط

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)