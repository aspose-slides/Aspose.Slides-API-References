---
title: get_ImageType()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "รับประเภทของภาพของอ็อบเจ็กต์ซูม. อ่าน ZoomImageType. ค่าเริ่มต้น: Preview"
type: docs
weight: 1
url: /th/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() เมธอด

รับประเภทของรูปภาพของอ็อบเจ็กต์ซูม. อ่าน [ZoomImageType](../../zoomimagetype/). ค่าเริ่มต้น: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## หมายเหตุ

ระบุว่าอ็อบเจ็กต์ Zoom ใช้การแสดงภาพตัวอย่างของสไลด์หรือรูปภาพหน้าปก

ตัวอย่างนี้แสดงการเปลี่ยน Image Type เป็นค่า Preview ในกรณีนี้รูปภาพปัจจุบันของอ็อบเจ็กต์ Zoom จะเปลี่ยนเป็นรูปภาพสไลด์:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## ดูเพิ่มเติม

* Enum [ZoomImageType](../../zoomimagetype/)
* คลาส [IZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)