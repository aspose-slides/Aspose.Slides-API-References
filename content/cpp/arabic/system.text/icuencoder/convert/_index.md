---
title: Convert()
second_title: مرجع API Aspose.Slides للغة C++
description: يحوِّل الأحرف إلى بايتات.
type: docs
weight: 66
url: /ar/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) طريقة


يحوِّل الأحرف إلى بايتات.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف للتشفير. |
| charIndex | int | إزاحة مخزن الإدخال. |
| charCount | int | حجم مخزن الإدخال. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن بايتات الوجهة. |
| byteIndex | int | إزاحة المصفوفة الوجهة. |
| byteCount | int | حجم المصفوفة الوجهة. |
| flush | **bool** | إذا كان true، ينظّف حالة الترميز الداخلية بعد الحساب. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف المقروءة. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغيّر ليُضبط على true إذا استُهلك مخزن الإدخال وإلى false غير ذلك. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) طريقة


يحوِّل الأحرف إلى بايتات.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | الأحرف للتشفير. |
| charCount | int | حجم مخزن الإدخال. |
| bytes | **uint8_t** * | مخزن بايتات الوجهة. |
| byteCount | int | حجم المصفوفة الوجهة. |
| flush | **bool** | إذا كان true، ينظّف حالة الترميز الداخلية بعد الحساب. |
| charsUsed | int\& | مرجع إلى المتغيّر لتخزين عدد الأحرف المقروءة. |
| bytesUsed | int\& | مرجع إلى المتغيّر لتخزين عدد البايتات المكتوبة. |
| completed | **bool**\& | مرجع إلى المتغيّر ليُضبط على true إذا استُهلك مخزن الإدخال وإلى false غير ذلك. |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [ICUEncoder](../)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)