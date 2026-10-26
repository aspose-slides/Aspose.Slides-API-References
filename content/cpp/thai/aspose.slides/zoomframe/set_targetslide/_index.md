---
title: set_TargetSlide()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดวัตถุสไลด์ที่ออบเจ็กต์ Slide Zoom เชื่อมโยงไปยัง เขียน ISlide.
type: docs
weight: 14
url: /th/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) เมธอด


กำหนดวัตถุสไลด์ที่ออบเจ็กต์ Zoom [Slide](../../slide/) เชื่อมโยงไปยัง เขียน [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## หมายเหตุ


ตัวอย่างต่อไปแสดงการเปลี่ยนสไลด์เป้าหมายและสร้างภาพใหม่สำหรับออบเจ็กต์ Zoom [Slide](../../slide/): 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [ZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)