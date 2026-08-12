---
title: set_TileAlignment()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดวิธีการจัดแนวเทกเจอร์ภายในรูปทรง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลวดลายเทกเจอร์และวิธีการทำซ้ำทั่วรูปทรง เขียน RectangleAlignment.
type: docs
weight: 391
url: /th/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) เมธอด


กำหนดวิธีการจัดแนวเทกเจอร์ภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลวดลายเทกเจอร์และวิธีที่มันทำซ้ำทั่วรูปร่าง เขียน [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## หมายเหตุ


ค่าเริ่มต้นคือ [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการจัดแนวของการเรียงต่อเป็นด้านล่างขวา
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## ดูเพิ่มเติม

* ชนิด Enum [RectangleAlignment](../../rectanglealignment/)
* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)