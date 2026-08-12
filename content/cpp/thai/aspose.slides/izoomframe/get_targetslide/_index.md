---
title: get_TargetSlide()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รับออบเจกต์สไลด์ที่วัตถุ Slide Zoom เชื่อมโยงไป อ่าน ISlide.
type: docs
weight: 1
url: /th/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() เมธอด

รับออบเจกต์สไลด์ที่วัตถุ Zoom [Slide](../../slide/) เชื่อมโยงไป อ่าน [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## หมายเหตุ

ตัวอย่างต่อไปแสดงการเปลี่ยนสไลด์เป้าหมายและสร้างภาพใหม่สำหรับวัตถุ Zoom [Slide](../../slide/):

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