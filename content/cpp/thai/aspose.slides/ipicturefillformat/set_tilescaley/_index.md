---
title: set_TileScaleY()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตั้งค่าค่าสเกลแนวตั้งสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียนเป็น float.
type: docs
weight: 365
url: /th/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) เมธอด

ตั้งค่าค่าสเกลแนวตั้งสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของ shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าค่าสเกลแนวตั้งสำหรับพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleY(120.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)