---
title: get_TransitionDuration()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "รับค่าระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์. อ่าน float. ค่าเริ่มต้น: 1.0f"
type: docs
weight: 105
url: /th/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() เมธอด


รับค่าระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์. อ่าน **float**. ค่าเริ่มต้น: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## หมายเหตุ


หากไม่ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนสไลด์ของปลายทางและเวลาเชื่อมโยงกับการเปลี่ยนนั้น. 

ตัวอย่างต่อไปนี้แสดงการเปลี่ยนระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์: 
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