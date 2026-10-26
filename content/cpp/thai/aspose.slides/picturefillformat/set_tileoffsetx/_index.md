---
title: set_TileOffsetX()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดการเยื้องแนวนอนของพื้นผิวจากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าบวกจะย้ายพื้นผิวไปทางขวา ในขณะที่ค่าลบจะย้ายไปทางซ้าย เขียนเป็น float.
type: docs
weight: 287
url: /th/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) เมธอด

กำหนดการเยื้องแนวนอนของพื้นผิวจากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าบวกจะย้ายพื้นผิวไปทางขวา ในขณะที่ค่าลบจะย้ายไปทางซ้าย เขียนเป็น **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเยื้องแนวนอนของพื้นผิวเป็น 20 จุด
pictureFillFormat->set_TileOffsetX(20.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)