---
title: get_TileFlip()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "พลิกไทล์พื้นผิวตามแกนแนวนอน, แนวตั้ง หรือทั้งสองแกน. อ่าน Slides::TileFlip."
type: docs
weight: 404
url: /th/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() เมธอด


พลิกไทล์พื้นผิวตามแกนแนวนอน, แนวตั้ง หรือทั้งสองแกน. อ่าน [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## หมายเหตุ


ค่าเริ่มต้นคือ [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// พลิกไทล์พื้นผิวตามแกนแนวตั้ง.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## ดูเพิ่มเติม

* Enum [TileFlip](../../tileflip/)
* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)