---
title: get_ShowBackground()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "รับค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ อ่าน bool. ค่าเริ่มต้น: true"
type: docs
weight: 53
url: /th/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() เมธอด

รับค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน **bool**. ค่าเริ่มต้น: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
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

* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)