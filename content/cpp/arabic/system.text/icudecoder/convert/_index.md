---
title: Convert()
second_title: مرجع API Aspose.Slides للغة C++
description: يحول البايتات إلى أحرف.
type: docs
weight: 66
url: /ar/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) طريقة

يحوِّل البايتات إلى أحرف.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات المطلوب فك ترميزها. |
| byteIndex | int | إزاحة المخزن المؤقت للمدخلات. |
| byteCount | int | حجم المخزن المؤقت للمدخلات. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف الوجهة. |
| charIndex | int | إزاحة المصفوفة الوجهة. |
| charCount | int | حجم المصفوفة الوجهة. |
| flush | **bool** | إذا كان true، يتم مسح حالة المفكّك الداخلية بعد الحساب. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات المقروءة. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغيّر ليُضبط على true إذا استُهلك مخزن المؤقت للمدخلات وإلا تُضبط على false. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) طريقة

يحوِّل البايتات إلى أحرف.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | البايتات المطلوب فك ترميزها. |
| byteCount | int | حجم المخزن المؤقت للمدخلات. |
| chars | char_t * | مخزن الأحرف الوجهة. |
| charCount | int | حجم المصفوفة الوجهة. |
| flush | **bool** | إذا كان true، يتم مسح حالة المفكّك الداخلية بعد الحساب. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات المقروءة. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغيّر ليُضبط على true إذا استُهلك مخزن المؤقت للمدخلات وإلا تُضبط على false. |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)