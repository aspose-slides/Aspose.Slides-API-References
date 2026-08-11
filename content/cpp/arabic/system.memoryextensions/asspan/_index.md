---
title: AsSpan()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نطاقًا من مصفوفة.
type: docs
weight: 1
url: /ar/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) دالة

ينشئ نطاقًا من مصفوفة.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المصفوفة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | مصفوفة المصدر. |
| start | **int32_t** | الفهرس الابتدائي في المصفوفة. |
| length | **int32_t** | طول النطاق. |

### قيمة الإرجاع

Span<T> يغطي الجزء المحدد من المصفوفة.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) دالة

ينشئ نطاقًا للقراءة فقط من سلسلة.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | سلسلة المصدر. |
| start | **int32_t** | الفهرس الابتدائي في السلسلة. |
| length | **int32_t** | طول النطاق. |

### قيمة الإرجاع

ReadOnlySpan<char16_t> يغطي الجزء المحدد من السلسلة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../system/arrayptr/)
* فئة [Span](../../system/span/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [String](../../system/string/)
* نطاق أسماء [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)