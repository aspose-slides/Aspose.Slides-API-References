---
title: set_TileFlip()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "พลิกพื้นผิวไทล์ตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน. เขียน Slides::TileFlip."
type: docs
weight: 417
url: /th/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) เมธอด

พลิกพื้นผิวไทล์ตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน. เขียน [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## หมายเหตุ

ค่าเริ่มต้นคือ [TileFlip::NoFlip](../../tileflip/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// ดึงรูปแบบการเติมภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// พลิกไทล์พื้นผิวตามแกนแนวตั้ง.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## ดูเพิ่มเติม

* Enum [TileFlip](../../tileflip/)
* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)