---
title: get_TileOffsetY()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าการเยื้องแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะทำให้พื้นผิวเลื่อนลง ส่วนค่าเป็นลบจะเลื่อนขึ้น อ่าน float.
type: docs
weight: 300
url: /th/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() เมธอด


คืนค่าการเยื้องแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะทำให้พื้นผิวเลื่อนลง ส่วนค่าเป็นลบจะเลื่อนขึ้น อ่าน **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเยื้องแนวตั้งของพื้นผิวเป็น -50 จุด
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)