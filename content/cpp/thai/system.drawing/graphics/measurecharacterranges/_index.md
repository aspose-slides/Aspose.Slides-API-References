---
title: MeasureCharacterRanges()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: ส่งกลับอาร์เรย์ของพื้นที่แต่ละส่วนที่ล้อมรอบตำแหน่งอักขระในสตริงที่ระบุ
type: docs
weight: 508
url: /th/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String&, const SharedPtr<Font>&, RectangleF, const SharedPtr<StringFormat>&) method

ส่งกลับอาร์เรย์ของพื้นที่แต่ละส่วนที่ล้อมรอบตำแหน่งอักขระในสตริงที่ระบุ

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)& | สตริงที่ต้องการวัด |
| font | const [SharedPtr](../../../system/sharedptr/)<[Font](../../font/)>& | ฟอนต์ที่ใช้ระหว่างการวัดสตริง |
| layoutRect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมผังแบบที่ใช้ระหว่างการวัดสตริง |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)<[StringFormat](../../stringformat/)>& | รูปแบบสตริงที่มีช่วงอักขระที่ต้องวัด |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Region](../../region/)
* คลาส [String](../../../system/string/)
* คลาส [Font](../../font/)
* คลาส [RectangleF](../../rectanglef/)
* คลาส [StringFormat](../../stringformat/)
* คลาส [Graphics](../)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)