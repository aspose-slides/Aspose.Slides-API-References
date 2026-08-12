---
title: set_TransitionDuration()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดระยะเวลาการเปลี่ยนระหว่าง Zoom กับสไลด์ เขียนเป็น float ค่าเริ่มต้น: 1.0f"
type: docs
weight: 118
url: /th/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) เมธอด


กำหนดระยะเวลาการเปลี่ยนระหว่าง Zoom กับสไลด์ เขียนเป็น **float** ค่าเริ่มต้น: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## หมายเหตุ


หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนสไลด์ปลายทางและเวลา ที่เชื่อมโยงกับการเปลี่ยนนั้น 

ตัวอย่างแสดงการเปลี่ยนระยะเวลาการเปลี่ยนระหว่าง Zoom กับสไลด์: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## ดูเพิ่มเติม

* คลาส [IZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)