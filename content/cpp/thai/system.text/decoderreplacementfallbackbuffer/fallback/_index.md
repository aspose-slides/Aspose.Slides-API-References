---
title: Fallback()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จัดการการล้มเหลวของการถอดรหัส.
type: docs
weight: 27
url: /th/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) เมธอด

จัดการกับการล้มเหลวของการถอดรหัส.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) ของไบต์ที่ไม่รู้จัก; ถูกละเว้น. |
| index | int | ออฟเซ็ตของไบต์ที่ไม่รู้จัก; ถูกละเว้น. |

### ค่าที่ส่งคืน

True หากสตริงการแทนที่ถูกกำหนดและไม่ว่างเปล่า, false ในกรณีอื่น.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [DecoderReplacementFallbackBuffer](../)
* เนมส페ซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)