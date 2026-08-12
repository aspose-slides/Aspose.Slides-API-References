---
title: get_TargetSection()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับอ็อบเจ็กต์ส่วนที่อ็อบเจ็กต์ Section Zoom ลิงก์ไปหา. อ่าน ISection.
type: docs
weight: 1
url: /th/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() เมธอด

รับอ็อบเจ็กต์ส่วนที่อ็อบเจ็กต์ Zoom [Section](../../section/) ลิงก์ไปหา. อ่าน [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงการเปลี่ยนส่วนเป้าหมายและสร้างภาพใหม่สำหรับอ็อบเจ็กต์ section zoom:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [SectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)