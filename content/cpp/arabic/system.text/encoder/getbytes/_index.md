---
title: GetBytes()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: احصل على البايتات الناتجة عن ترميز مخزن مؤقت.
type: docs
weight: 53
url: /ar/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) طريقة

احصل على البايتات الناتجة عن ترميز مخزن مؤقت.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف المطلوب ترميزها. |
| charIndex | int | إزاحة مصفوفة المصدر. |
| charCount | int | طول الجزء الفرعي من المصدر. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن البايتات الوجهة. |
| byteIndex | int | إزاحة مخزن الوجهة. |
| flush | **bool** | إذا كان صحيحًا، يُنظّف حالة المشفر الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) طريقة

احصل على البايتات الناتجة عن ترميز مخزن مؤقت.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف المطلوب ترميزها. |
| charCount | int | طول مصفوفة المصدر. |
| bytes | **uint8_t** * | مخزن البايتات الوجهة. |
| byteCount | int | حجم مخزن الوجهة. |
| flush | **bool** | إذا كان صحيحًا، يُنظّف حالة المشفر الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Encoder](../)
* فضاء الاسم [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)