---
title: set_GridSpacing()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าระยะห่างของตารางที่ควรใช้สำหรับตารางพื้นฐานของเอกสารนำเสนอในหน่วยจุด เขียนเป็น float.
type: docs
weight: 105
url: /th/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) เมธอด


ตั้งค่าระยะห่างของตารางที่ควรใช้สำหรับตารางพื้นฐานของเอกสารนำเสนอในหน่วยจุด เขียนเป็น **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## หมายเหตุ


ค่าระยะห่างของตารางต้องเป็นจำนวนบวก ช่วงค่าที่ทั่วไปคือจาก 1 มม. (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด). 

โค้ดตัวอย่างต่อไปนี้แสดงวิธีเปลี่ยนระยะห่างของตารางในงานนำเสนอ PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [ViewProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)