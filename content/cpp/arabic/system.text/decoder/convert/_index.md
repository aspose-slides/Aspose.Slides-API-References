---
title: Convert()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل البايتات إلى أحرف.
type: docs
weight: 79
url: /ar/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) طريقة

يقوم بتحويل البايتات إلى أحرف.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات المراد فك تشفيرها. |
| byteIndex | int | إزاحة مخزن الإدخال. |
| byteCount | int | حجم مخزن الإدخال. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف الوجهة. |
| charIndex | int | إزاحة مصفوفة الوجهة. |
| charCount | int | حجم مصفوفة الوجهة. |
| flush | **bool** | إذا كان true، ينظف حالة المفكك الداخلية بعد الحساب. |
| bytesUsed | int\& | مرجع إلى المتغير لتخزين عدد البايتات المقروءة. |
| charsUsed | int\& | مرجع إلى المتغير لتخزين عدد الأحرف المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغير ليُضبط إلى true إذا استُهلك مخزن الإدخال وإلى false غير ذلك. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) طريقة

يقوم بتحويل البايتات إلى أحرف.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | البايتات المراد فك تشفيرها. |
| byteCount | int | حجم مخزن الإدخال. |
| chars | char_t * | مخزن الأحرف الوجهة. |
| charCount | int | حجم مصفوفة الوجهة. |
| flush | **bool** | إذا كان true، ينظف حالة المفكك الداخلية بعد الحساب. |
| bytesUsed | int\& | مرجع إلى المتغير لتخزين عدد البايتات المقروءة. |
| charsUsed | int\& | مرجع إلى المتغير لتخزين عدد الأحرف المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغير ليُضبط إلى true إذا استُهلك مخزن الإدخال وإلى false غير ذلك. |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Decoder](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)