---
title: set_ShowBackground()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ตั้งค่าค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ เขียนเป็น bool ค่าเริ่มต้น: true"
type: docs
weight: 66
url: /th/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) เมธอด


ตั้งค่าค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ เขียนเป็น **bool** ค่าเริ่มต้น: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## หมายเหตุ


ตัวอย่างนี้แสดงการลบพื้นหลังของภาพของอ็อบเจกต์ Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## ดูเพิ่มเติม

* คลาส [ZoomObject](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)