---
title: set_TileOffsetY()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดการเลื่อนแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปในหน่วยจุด ค่าบวกจะทำให้พื้นผิวเลื่อนลง ส่วนค่าลบจะทำให้พื้นผิวเลื่อนขึ้น เขียน float.
type: docs
weight: 313
url: /th/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) เมธอด


กำหนดการเลื่อนแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปในหน่วยจุด ค่าบวกจะทำให้พื้นผิวเลื่อนลง ส่วนค่าลบจะทำให้พื้นผิวเลื่อนขึ้น เขียน **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเลื่อนแนวตั้งของพื้นผิวเป็น -50 จุด
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)