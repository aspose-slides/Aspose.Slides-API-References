---
title: get_TargetSection()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รับอ็อบเจ็กต์ส่วนที่อ็อบเจ็กต์ Section Zoom เชื่อมโยงไปยัง. อ่าน ISection.
type: docs
weight: 1
url: /th/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() เมธอด


รับอ็อบเจ็กต์ส่วนที่ [Section](../../section/) Zoom เชื่อมโยงไปยัง. อ่าน [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## หมายเหตุ


ตัวอย่างนี้แสดงการเปลี่ยนส่วนเป้าหมายและสร้างภาพใหม่สำหรับอ็อบเจ็กต์การซูมส่วน: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [ISection](../../isection/)
* คลาส [ISectionZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)