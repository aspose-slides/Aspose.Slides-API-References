---
title: set_TileOffsetX()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดการเลื่อนแนวนอนของพื้นผิวจากตำแหน่งต้นของรูปร่างเป็นหน่วยพอยต์ ค่าเชิงบวกจะเลื่อนพื้นผิวไปด้านขวา ส่วนค่าเชิงลบจะเลื่อนไปด้านซ้าย เขียนเป็น float.
type: docs
weight: 287
url: /th/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) เมธอด


กำหนดการเลื่อนแนวนอนของพื้นผิวจากตำแหน่งต้นของรูปร่างเป็นหน่วยพอยต์ ค่าบวกจะเลื่อนพื้นผิวไปด้านขวา ในขณะที่ค่าลบจะเลื่อนไปด้านซ้าย เขียน **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งการเลื่อนแนวนอนของพื้นผิวเป็น 20 พอยต์
pictureFillFormat->set_TileOffsetX(20.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)