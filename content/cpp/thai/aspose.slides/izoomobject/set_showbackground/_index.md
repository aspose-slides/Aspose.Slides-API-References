---
title: set_ShowBackground()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ เขียนเป็น bool ค่าเริ่มต้น: true"
type: docs
weight: 66
url: /th/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) method


กำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ เขียนเป็น **bool** ค่าเริ่มต้น: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## หมายเหตุ


ตัวอย่างนี้แสดงการลบพื้นหลังของภาพของอ็อบเจ็กต์ Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## ดูเพิ่มเติม

* คลาส [IZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)