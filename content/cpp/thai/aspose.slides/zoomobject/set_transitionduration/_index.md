---
title: set_TransitionDuration()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "กำหนดระยะเวลาในการเปลี่ยนแปลงระหว่าง Zoom และสไลด์ เขียนเป็น float ค่าเริ่มต้น: 1.0f"
type: docs
weight: 118
url: /th/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) เมธอด


กำหนดระยะเวลาในการเปลี่ยนแปลงระหว่าง Zoom และสไลด์ เขียนเป็น **float** ค่าเริ่มต้น: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## หมายเหตุ


หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนสไลด์ปลายทางและเวลาที่เชื่อมโยงกับการเปลี่ยนนั้น

ตัวอย่างแสดงการเปลี่ยนแปลงระยะเวลาในการเปลี่ยนแปลงระหว่าง Zoom และสไลด์: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## ดูเพิ่มเติม

* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)