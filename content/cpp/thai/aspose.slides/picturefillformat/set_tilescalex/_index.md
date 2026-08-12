---
title: set_TileScaleX()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ตั้งค่าขนาดแนวนอนสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียนเป็น float.
type: docs
weight: 339
url: /th/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) เมธอด


ตั้งค่าขนาดแนวนอนสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์. เขียน **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// ดึงรูปแบบการเติมรูปภาพของรูปทรง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าขนาดแนวนอนของพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleX(120.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)