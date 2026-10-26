---
title: get_ZoomImage()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับภาพสำหรับวัตถุซูม. อ่าน IPPImage.
type: docs
weight: 79
url: /th/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() เมธอด


รับภาพสำหรับวัตถุซูม. อ่าน [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## หมายเหตุ


ตัวอย่างนี้แสดงการเปลี่ยนภาพของวัตถุซูม: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)