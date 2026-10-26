---
title: set_TargetSlide()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตั้งค่าอ็อบเจกต์สไลด์ที่วัตถุ Slide Zoom เชื่อมโยงถึง. เขียน ISlide.
type: docs
weight: 14
url: /th/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) เมธอด

ตั้งค่าอ็อบเจกต์สไลด์ที่วัตถุ [Slide](../../slide/) Zoom เชื่อมโยงถึง. เขียน [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## หมายเหตุ

ตัวอย่างถัดไปแสดงการเปลี่ยนสไลด์เป้าหมายและสร้างภาพใหม่สำหรับวัตถุ [Slide](../../slide/) Zoom:

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [IZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)