---
title: set_TargetSection()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: กำหนดอ็อบเจ็กต์ส่วนที่อ็อบเจ็กต์ Section Zoom เชื่อมโยงไป. เขียน ISection.
type: docs
weight: 14
url: /th/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) เมธอด


กำหนดอ็อบเจ็กต์ส่วนที่อ็อบเจ็กต์ Zoom [Section](../../section/) เชื่อมโยงไป. เขียน [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## หมายเหตุ


ตัวอย่างต่อไปแสดงการเปลี่ยนส่วนเป้าหมายและสร้างภาพใหม่สำหรับอ็อบเจ็กต์ section zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISection](../../isection/)
* คลาส [SectionZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)