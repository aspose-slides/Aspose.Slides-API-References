---
title: set_TileScaleY()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดสเกลแนวตั้งสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียนเป็น float.
type: docs
weight: 365
url: /th/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) เมธอด

กำหนดสเกลแนวตั้งสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียนเป็น **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งสเกลแนวตั้งสำหรับพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleY(120.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)