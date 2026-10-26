---
title: set_TileFlip()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "พลิกไทล์พื้นผิวตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน. เขียน Slides::TileFlip."
type: docs
weight: 417
url: /th/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) เมธอด


พลิกไทล์พื้นผิวตามแนวนอน แนวตั้ง หรือทั้งสองแกน. เขียน [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## หมายเหตุ


ค่าเริ่มต้นคือ [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// พลิกไทล์พื้นผิวตามแกนแนวตั้ง.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## ดูเพิ่มเติม

* Enum [TileFlip](../../tileflip/)
* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)