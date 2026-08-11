---
title: Fallback()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتعامل مع فشل فك الترميز.
type: docs
weight: 27
url: /ar/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) طريقة


Handles decoding failure.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) من البايتات غير المعروفة؛ يتم تجاهلها. |
| index | int | إزاحة البايتات غير المعروفة؛ يتم تجاهلها. |

### قيمة الإرجاع

True إذا تم توفير سلسلة الاستبدال ولم تكن فارغة، false خلاف ذلك.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* الفئة [DecoderReplacementFallbackBuffer](../)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)