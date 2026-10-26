---
title: Convert()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل الأحرف إلى بايتات.
type: docs
weight: 79
url: /ar/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

يقوم بتحويل الحروف إلى بايتات.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف لتشفيرها. |
| charIndex | int | موضع مخزن الإدخال. |
| charCount | int | حجم مخزن الإدخال. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن البايتات الوجهة. |
| byteIndex | int | إزاحة المصفوفة الوجهة. |
| byteCount | int | حجم المصفوفة الوجهة. |
| flush | **bool** | إذا true، ينظف حالة المشفر الداخلية بعد الحساب. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف المقروءة. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغيّر ليُضبط على true إذا استُنفد مخزن الإدخال وإلا على false. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

يقوم بتحويل الحروف إلى بايتات.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف لتشفيرها. |
| charCount | int | حجم مخزن الإدخال. |
| bytes | **uint8_t** * | مخزن البايتات الوجهة. |
| byteCount | int | حجم المصفوفة الوجهة. |
| flush | **bool** | إذا true، ينظف حالة المشفر الداخلية بعد الحساب. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف المقروءة. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغيّر ليُضبط على true إذا استُنفد مخزن الإدخال وإلا على false. |

## انظر أيضًا

* تعريف_نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Encoder](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)