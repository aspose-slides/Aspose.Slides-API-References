---
title: get_Sections()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع قائمة بجميع أقسام الشرائح التي تم تعريفها في العرض التقديمي. ISectionCollection للقراءة فقط.
type: docs
weight: 66
url: /ar/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() طريقة

يرجع قائمة بجميع أقسام الشرائح التي تم تعريفها في العرض التقديمي. للقراءة فقط [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## ملاحظات

تُظهر الأمثلة التالية كيفية إنشاء أقسام في PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// ستنتهي section1 عند newSlide2 وبعد ذلك سيبدأ section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 تُظهر الأمثلة التالية كيفية تغيير أسماء الأقسام. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISectionCollection](../../isectioncollection/)
* فئة [Presentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)