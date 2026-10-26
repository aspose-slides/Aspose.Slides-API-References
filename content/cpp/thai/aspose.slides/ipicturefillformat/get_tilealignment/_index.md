---
title: get_TileAlignment()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนวิธีที่เทกเจอร์จัดแนวภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลายเทกเจอร์และวิธีที่มันทำซ้ำทั่วรูปร่าง อ่าน RectangleAlignment.
type: docs
weight: 378
url: /th/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() เมธอด


ส่งคืนวิธีที่เทกเจอร์จัดแนวภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลายเทกเจอร์และวิธีที่มันทำซ้ำทั่วรูปร่าง อ่าน [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## หมายเหตุ


ค่าเริ่มต้นคือ [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปทรง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการจัดแนวของการทำกระเบื้องเป็นด้านล่างขวา
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## ดูเพิ่มเติม

* Enum [RectangleAlignment](../../rectanglealignment/)
* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)