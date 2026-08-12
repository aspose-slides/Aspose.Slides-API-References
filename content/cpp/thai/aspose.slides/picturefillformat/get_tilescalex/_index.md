---
title: get_TileScaleX()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนสเกลแนวนอนสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์. อ่าน float.
type: docs
weight: 326
url: /th/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() เมธอด

ส่งคืนสเกลแนวนอนสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์. อ่าน **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งสเกลแนวนอนสำหรับพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleX(120.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)