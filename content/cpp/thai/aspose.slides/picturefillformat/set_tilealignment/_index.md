---
title: set_TileAlignment()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดวิธีการจัดตำแหน่งเทกเจอร์ภายในรูปร่าง. การตั้งค่านี้ควบคุมจุดเริ่มต้นของลวดลายเทกเจอร์และวิธีการทำซ้ำทั่วรูปร่าง. เขียน RectangleAlignment.
type: docs
weight: 391
url: /th/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) เมธอด

กำหนดวิธีการจัดตำแหน่งเทกเจอร์ภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลวดลายเทกเจอร์และวิธีการทำซ้ำทั่วรูปร่าง เขียน [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## หมายเหตุ

ค่าเริ่มต้นคือ [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// ดึงรูปแบบการเติมรูปภาพของรูปทรง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งการจัดตำแหน่งการทำซ้ำให้ด้านล่างขวา
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## ดูเพิ่มเติม

* Enum [RectangleAlignment](../../rectanglealignment/)
* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)