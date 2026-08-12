---
title: get_TileOffsetX()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: ส่งคืนการเลื่อนแนวนอนของพื้นผิวจากจุดกำเนิดของรูปทรงเป็นจุด. ค่าบวกจะเลื่อนพื้นผิวไปทางขวา, ในขณะที่ค่าลบจะเลื่อนไปทางซ้าย. อ่าน float.
type: docs
weight: 274
url: /th/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() เมธอด


ส่งคืนการเลื่อนแนวนอนของพื้นผิวจากจุดกำเนิดของรูปทรงเป็นจุด. ค่าบวกจะเลื่อนพื้นผิวไปทางขวา, ในขณะที่ค่าลบจะเลื่อนไปทางซ้าย. อ่าน **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปทรง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าการเลื่อนแนวนอนของพื้นผิวเป็น 20 จุด
pictureFillFormat->set_TileOffsetX(20.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)