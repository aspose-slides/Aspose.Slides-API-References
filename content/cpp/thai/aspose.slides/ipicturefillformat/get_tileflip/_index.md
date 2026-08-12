---
title: get_TileFlip()
second_title: Aspose.Slides สำหรับ API ของ C++
description: "พลิกไทล์พื้นผิวตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน. อ่าน Slides::TileFlip."
type: docs
weight: 404
url: /th/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() เมธอด


พลิกพื้นผิวไทล์ตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน. อ่าน [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## หมายเหตุ


ค่าเริ่มต้นคือ [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// กำหนดโหมดการเติมภาพเป็น Tile
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