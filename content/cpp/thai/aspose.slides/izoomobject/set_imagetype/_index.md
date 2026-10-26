---
title: set_ImageType()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "กำหนดประเภทภาพของอ็อบเจ็กต์ซูม. เขียน ZoomImageType. ค่าเริ่มต้น: Preview"
type: docs
weight: 14
url: /th/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) เมธอด

ตั้งค่าประเภทภาพของวัตถุซูม เขียน [ZoomImageType](../../zoomimagetype/) ค่าเริ่มต้น: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## หมายเหตุ

ระบุว่าวัตถุ Zoom ใช้การแสดงตัวอย่างสไลด์หรือภาพปก

ตัวอย่างนี้แสดงการเปลี่ยน Image Type เป็นค่า Preview ในกรณีนี้ภาพปัจจุบันของวัตถุ Zoom จะเปลี่ยนเป็นภาพสไลด์:
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