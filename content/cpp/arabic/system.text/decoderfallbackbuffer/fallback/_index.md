---
title: Fallback()
second_title: مرجع API Aspose.Slides لـ C++
description: ينفّذ إجراء السقوط الفعلي.
type: docs
weight: 14
url: /ar/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) طريقة

ينفّذ إجراء السقوط الفعلي.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) من البايتات بما في ذلك تلك التي فشل المفكك في فك تشفيرها. |
| index | int | [Index](../../../system/index/) من البايت الذي تسبب بالخطأ. |

### قيمة الإرجاع

True إذا كان المخزن المؤقت يعالج البايتات غير المعروفة، false إذا كان يتجاهلها.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [DecoderFallbackBuffer](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)