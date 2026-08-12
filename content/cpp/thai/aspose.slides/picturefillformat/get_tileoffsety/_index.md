---
title: get_TileOffsetY()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่าการเยื้องแนวตั้งของพื้นผิวจากจุดเริ่มต้นของรูปร่างเป็นหน่วยจุด ค่าเชิงบวกจะเลื่อนพื้นผิวลง ส่วนค่าเชิงลบจะเลื่อนพื้นผิวขึ้น อ่าน float.
type: docs
weight: 300
url: /th/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() เมธอด

คืนค่าการเยื้องแนวตั้งของพื้นผิวจากจุดเริ่มต้นของรูปร่างเป็นหน่วยจุด ค่าเชิงบวกจะเลื่อนพื้นผิวลงด้านล่าง ส่วนค่าเชิงลบจะเลื่อนพื้นผิวขึ้นด้านบน อ่าน **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## หมายเหตุ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเยื้องแนวตั้งของพื้นผิวเป็น -50 จุด
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)