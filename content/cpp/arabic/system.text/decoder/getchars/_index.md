---
title: GetChars()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: احصل على الأحرف الناتجة عن فك ترميز مخزن مؤقت.
type: docs
weight: 53
url: /ar/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) طريقة

احصل على الأحرف الناتجة عن فك ترميز المخزن المؤقت.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات المراد فك ترميزها. |
| byteIndex | int | إزاحة المخزن المؤقت للمدخلات. |
| byteCount | int | حجم المخزن المؤقت للمدخلات. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف الهدف. |
| charIndex | int | إزاحة المصفوفة الهدف. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) طريقة

احصل على الأحرف الناتجة عن فك ترميز المخزن المؤقت.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات المراد فك ترميزها. |
| byteIndex | int | إزاحة المخزن المؤقت للمدخلات. |
| byteCount | int | حجم المخزن المؤقت للمدخلات. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف الهدف. |
| charIndex | int | إزاحة المصفوة الهدف. |
| flush | **bool** | إذا كان true، ينظف حالة المفكك الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) طريقة

احصل على الأحرف الناتجة عن فك ترميز المخزن المؤقت.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | البايتات المراد فك ترميزها. |
| byteCount | int | حجم المخزن المؤقت للمدخلات. |
| chars | char_t * | مخزن الأحرف الهدف. |
| charCount | int | حجم المصفوفة الهدف. |
| flush | **bool** | إذا كان true، ينظف حالة المفكك الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Decoder](../)
* مساحة الأسماء [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)