---
title: get_Sections()
second_title: مرجع API Aspose.Slides برای C++
description: فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی ISectionCollection.
type: docs
weight: 66
url: /fa/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() متد

فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## ملاحظات

مثال‌های زیر نشان می‌دهند چگونه بخش‌ها را در یک PowerPoint [Presentation](../) ایجاد کنید. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 در newSlide2 پایان می‌یابد و پس از آن section2 شروع می‌شود
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 مثال‌های زیر نشان می‌دهند چگونه نام‌های بخش‌ها را تغییر دهید. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISectionCollection](../../isectioncollection/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)