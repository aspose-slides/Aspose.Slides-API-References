---
title: get_TileScaleY()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งค่าตั้งค่าสเกลแนวตั้งของการเติมพื้นผิวเป็นเปอร์เซ็นต์ อ่าน float.
type: docs
weight: 352
url: /th/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() เมธอด


Returns the vertical scale for the texture fill as a percentage. Read **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าสเกลแนวตั้งของพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleY(120.0f);
```

## ดูเพิ่มเติม

* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)