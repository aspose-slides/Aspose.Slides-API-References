---
title: get_TransitionDuration()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "รับค่าระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และ slide. อ่าน float. ค่าเริ่มต้น: 1.0f"
type: docs
weight: 105
url: /th/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() เมธodb

รับค่าระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และสไลด์ อ่าน **float** ค่าเริ่มต้น: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## หมายเหตุ

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านสไลด์ปลายทางและเวลาในการเปลี่ยนผ่านที่สัมพันธ์กับการเปลี่ยนนั้น

ตัวอย่างแสดงการเปลี่ยนแปลงระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และสไลด์:
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