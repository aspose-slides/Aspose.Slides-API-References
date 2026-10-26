---
title: set_TileScaleX()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดสเกลแนวนอนสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียน float.
type: docs
weight: 339
url: /th/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) เมธอด


กำหนดสเกลแนวนอนสำหรับการเติมพื้นผิวเป็นเปอร์เซ็นต์ เขียน **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับรูปแบบการเติมภาพของรูปทรง
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ตั้งค่าโหมดการเติมภาพเป็น Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// ตั้งค่าสเกลแนวนอนสำหรับพื้นผิวเป็น 120 เปอร์เซ็นต์
pictureFillFormat->set_TileScaleX(120.0f);
```

## ดูเพิ่มเติม

* คลาส [IPictureFillFormat](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)