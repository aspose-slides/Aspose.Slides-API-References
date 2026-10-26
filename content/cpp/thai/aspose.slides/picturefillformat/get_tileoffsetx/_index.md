---
title: get_TileOffsetX()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนการเลื่อนแนวนอนของพื้นผิวจากตำแหน่งต้นของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะเลื่อนพื้นผิวไปทางขวา ส่วนค่าเป็นลบจะเลื่อนไปทางซ้าย อ่าน float.
type: docs
weight: 274
url: /th/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() เมธอด

Returns the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเลื่อนแนวนอนของพื้นผิวเป็น 20 จุด
pictureFillFormat->set_TileOffsetX(20.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)