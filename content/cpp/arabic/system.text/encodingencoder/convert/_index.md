---
title: Convert()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل الأحرف إلى بايتات.
type: docs
weight: 1
url: /ar/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

يقوم بتحويل الأحرف إلى بايتات.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف المراد ترميزها. |
| charCount | int | حجم المخزن المؤقت للمدخلات. |
| bytes | **uint8_t** * | مخزن بايتات الوجهة. |
| byteCount | int | حجم مصفوفة الوجهة. |
| flush | **bool** | إذا كان true، ينظّف حالة الترميز الداخلية بعد الحساب. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف التي تم قراءتها. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات التي تم كتابتها. |
| completed | **bool**\& | مرجع إلى المتغيّر لتعيينه إلى true إذا استُهلك مخزن المدخلات وإلى false خلاف ذلك. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

يقوم بتحويل الأحرف إلى بايتات.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف المراد ترميزها. |
| charIndex | int | إزاحة مخزن المدخلات. |
| charCount | int | حجم مخزن المدخلات. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن بايتات الوجهة. |
| byteIndex | int | إزاحة مصفوفة الوجهة. |
| byteCount | int | حجم مصفوفة الوجهة. |
| flush | **bool** | إذا كان true، ينظّف حالة الترميز الداخلية بعد الحساب. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف التي تم قراءتها. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات التي تم كتابتها. |
| completed | **bool**\& | مرجع إلى المتغيّر لتعيينه إلى true إذا استُهلك مخزن المدخلات وإلى false خلاف ذلك. |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [EncodingEncoder](../)
* نطاق الاسم [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)