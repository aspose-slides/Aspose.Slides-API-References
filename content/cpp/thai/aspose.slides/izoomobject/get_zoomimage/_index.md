---
title: get_ZoomImage()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับภาพสำหรับอ็อบเจกต์ซูม. อ่าน IPPImage.
type: docs
weight: 79
url: /th/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() เมธอด

รับภาพสำหรับอ็อบเจกต์ซูม อ่าน [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## หมายเหตุ

ตัวอย่างแสดงการเปลี่ยนภาพของอ็อบเจกต์ซูม: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [IZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)