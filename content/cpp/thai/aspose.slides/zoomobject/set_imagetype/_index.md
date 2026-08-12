---
title: set_ImageType()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "กำหนดประเภทภาพของวัตถุซูม เขียน ZoomImageType ค่าเริ่มต้น: Preview"
type: docs
weight: 14
url: /th/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) เมธอด

กำหนดประเภทภาพของวัตถุซูม เขียน [ZoomImageType](../../zoomimagetype/) ค่าเริ่มต้น: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## หมายเหตุ

ระบุว่า Zoom object ใช้การแสดงตัวอย่างสไลด์หรือภาพปก

ตัวอย่างต่อไปนี้แสดงการเปลี่ยน Image Type เป็นค่า Preview ในกรณีนี้ภาพปัจจุบันของ Zoom object จะเปลี่ยนเป็นภาพสไลด์:

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## ดูเพิ่มเติม

* Enum [ZoomImageType](../../zoomimagetype/)
* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)