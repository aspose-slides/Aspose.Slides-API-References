---
title: Fallback()
second_title: مرجع API Aspose.Slides للغة C++
description: يتعامل مع فشل فك الترميز.
type: docs
weight: 27
url: /ar/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) طريقة

يتعامل مع فشل فك الترميز.

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) من البايتات غير المعروفة؛ تم تجاهله. |
| index | int | إزاحة البايتات غير المعروفة؛ تم تجاهلها. |

### قيمة الإرجاع

لا يعود فعليًا أبدا، بل يرمي الاستثناء بدلاً من ذلك.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [DecoderExceptionFallbackBuffer](../)
* مساحة اسم [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)