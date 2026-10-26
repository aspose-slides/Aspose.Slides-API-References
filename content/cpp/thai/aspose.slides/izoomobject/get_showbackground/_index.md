---
title: get_ShowBackground()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "รับค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ อ่าน bool ค่าปริยาย: true"
type: docs
weight: 53
url: /th/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() เมธอด

รับค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ อ่าน **bool** ค่าปริยาย: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
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

* คลาส [IZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)