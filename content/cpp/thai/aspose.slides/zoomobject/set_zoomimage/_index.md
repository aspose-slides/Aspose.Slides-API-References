---
title: set_ZoomImage()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตั้งค่าภาพสำหรับอ็อบเจ็กต์ซูม เขียน IPPImage.
type: docs
weight: 92
url: /th/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) เมธอด

ตั้งค่าภาพสำหรับอ็อบเจ็กต์ซูม. เขียน [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## หมายเหตุ

ตัวอย่างจะแสดงการเปลี่ยนภาพของอ็อบเจ็กต์ Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)