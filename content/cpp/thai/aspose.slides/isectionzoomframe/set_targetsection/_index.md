---
title: set_TargetSection()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตั้งค่าตัวอ็อบเจ็กต์ส่วนที่เชื่อมต่อกับวัตถุ Section Zoom. เขียน ISection.
type: docs
weight: 14
url: /th/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) เมธอด


ตั้งค่าตัวอ็อบเจ็กต์ส่วนที่เชื่อมต่อกับวัตถุ Zoom [Section](../../section/). เขียน [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## หมายเหตุ


ตัวอย่างนี้แสดงการเปลี่ยนส่วนเป้าหมายและสร้างภาพใหม่สำหรับวัตถุ section zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISection](../../isection/)
* คลาส [ISectionZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)