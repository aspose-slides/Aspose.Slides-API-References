---
title: GetBytes()
second_title: Aspose.Slides لـ C++ مرجع API
description: احصل على البايتات الناتجة عن ترميز مخزن مؤقت.
type: docs
weight: 53
url: /ar/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method

احصل على البايتات الناتجة عن تشفير مخزن مؤقت.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف للترميز. |
| charIndex | int | إزاحة مصفوفة المصدر. |
| charCount | int | طول المصفوفة الفرعية للمصدر. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن بايت الوجهة. |
| byteIndex | int | إزاحة مخزن الوجهة. |
| flush | **bool** | إذا كان true، ينظّف حالة الترميز الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method

احصل على البايتات الناتجة عن تشفير مخزن مؤقت.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف للترميز. |
| charCount | int | طول مصفوفة المصدر. |
| bytes | **uint8_t** * | مخزن بايت الوجهة. |
| byteCount | int | حجم مخزن الوجهة. |
| flush | **bool** | إذا كان true، ينظّف حالة الترميز الداخلية بعد الحساب. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [ICUEncoder](../)
* مساحة الاسم [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)