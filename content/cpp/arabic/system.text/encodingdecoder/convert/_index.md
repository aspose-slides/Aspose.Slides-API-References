---
title: Convert()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يحول البايتات إلى أحرف.
type: docs
weight: 1
url: /ar/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) طريقة


يقوم بتحويل البايتات إلى أحرف.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | البايتات المراد فك تشفيرها. |
| byteCount | int | حجم مخزن الإدخال. |
| chars | char_t * | مخزن الأحرف الوجهة. |
| charCount | int | حجم الصفيف الوجهة. |
| flush | **bool** | إذا كان true، يُنظّف حالة المفكك الداخلية بعد الحساب. |
| bytesUsed | int\& | إشارة إلى المتغيّر لتخزين عدد البايتات المقروءة. |
| charsUsed | int\& | إشارة إلى المتغيّر لتخزين عدد الأحرف المكتوبة. |
| completed | **bool**\& | إشارة إلى المتغيّر لتعيينه إلى true إذا استُهلك مخزن الإدخال وإلى false وإلا. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) طريقة


يقوم بتحويل البايتات إلى أحرف.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | البايتات المراد فك تشفيرها. |
| byteIndex | int | موضع المخزن الإدخالي. |
| byteCount | int | حجم مخزن الإدخال. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف الوجهة. |
| charIndex | int | موضع الصفيف الوجهة. |
| charCount | int | حجم الصفيف الوجهة. |
| flush | **bool** | إذا كان true، يُنظّف حالة المفكك الداخلية بعد الحساب. |
| bytesUsed | int\& | إشارة إلى المتغيّر لتخزين عدد البايتات المقروءة. |
| charsUsed | int\& | إشارة إلى المتغيّر لتخزين عدد الأحرف المكتوبة. |
| completed | **bool**\& | إشارة إلى المتغيّر لتعيينه إلى true إذا استُهلك مخزن الإدخال وإلى false وإلا. |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [EncodingDecoder](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)