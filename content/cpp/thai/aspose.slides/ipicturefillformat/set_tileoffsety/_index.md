---
title: set_TileOffsetY()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดการเลื่อนแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะทำให้พื้นผิวเลื่อนลงด้านล่าง ในขณะที่ค่าติดลบจะทำให้พื้นผิวเลื่อนขึ้น เขียนเป็น float.
type: docs
weight: 313
url: /th/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) เมธอด


กำหนดการเลื่อนแนวตั้งของพื้นผิวจากต้นกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะเลื่อนพื้นผิวลงด้านล่าง ในขณะที่ค่าลบจะเลื่อนขึ้น เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปทรง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเลื่อนแนวตั้งของพื้นผิวเป็น -50 จุด
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)