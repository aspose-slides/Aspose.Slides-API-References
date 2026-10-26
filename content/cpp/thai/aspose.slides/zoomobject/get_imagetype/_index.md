---
title: get_ImageType()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "ดึงประเภทของภาพของอ็อบเจ็กต์ซูม. อ่าน ZoomImageType. ค่าเริ่มต้น: Preview"
type: docs
weight: 1
url: /th/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() เมธอด

ดึงประเภทของภาพของอ็อบเจ็กต์ซูม. อ่าน [ZoomImageType](../../zoomimagetype/). ค่าเริ่มต้น: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## หมายเหตุ

ระบุว่าอ็อบเจ็กต์ Zoom ใช้การแสดงตัวอย่างสไลด์หรือภาพปก  

ตัวอย่างต่อไปแสดงการเปลี่ยน Image Type เป็นค่า Preview. ในกรณีนี้ภาพปัจจุบันของอ็อบเจ็กต์ Zoom จะเปลี่ยนเป็นภาพสไลด์: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## ดูเพิ่มเติม

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)