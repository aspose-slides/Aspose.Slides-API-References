---
title: get_TileScaleY()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนสเกลแนวตั้งสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์. อ่าน float.
type: docs
weight: 352
url: /th/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() เมธอด


ส่งคืนสเกลแนวตั้งสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ อ่าน **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// ดึงรูปแบบการเติมรูปภาพของรูปร่าง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งโหมดการเติมรูปภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งสเกลแนวตั้งสำหรับพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleY(120.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)