---
title: get_TileAlignment()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ส่งคืนวิธีที่พื้นผิวถูกจัดตำแหน่งภายในรูปทรง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลายพื้นผิวและวิธีที่ลายซ้ำทั่วรูปทรง อ่าน RectangleAlignment.
type: docs
weight: 378
url: /th/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() เมธอด

ส่งคืนวิธีที่พื้นผิวถูกจัดตำแหน่งภายในรูปทรง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลายพื้นผิวและวิธีที่ลายซ้ำทั่วรูปทรง อ่าน [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## หมายเหตุ

ค่าเริ่มต้นคือ [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมภาพเป็นแบบ Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการจัดตำแหน่งของการทำ Tile เป็นด้านล่างขวา
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## ดูเพิ่มเติม

* Enum [RectangleAlignment](../../rectanglealignment/)
* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)