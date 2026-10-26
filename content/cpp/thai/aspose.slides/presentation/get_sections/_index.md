---
title: get_Sections()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดไว้ในงานนำเสนอ. อ่านอย่างเดียว ISectionCollection.
type: docs
weight: 66
url: /th/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() เมธอด


ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดไว้ในงานนำเสนอ. อ่านอย่างเดียว [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีสร้าง Sections ใน PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 จะสิ้นสุดที่ newSlide2 และหลังจากนั้น section2 จะเริ่มต้น
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนชื่อของ Sections. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISectionCollection](../../isectioncollection/)
* คลาส [Presentation](../)
* เนมส페ซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)