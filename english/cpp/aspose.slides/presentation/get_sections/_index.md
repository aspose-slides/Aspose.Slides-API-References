---
title: get_Sections()
second_title: Aspose.Slides for C++ API Reference
description: Returns a list of all slides sections that are defined in the presentation. Read-only ISectionCollection.
type: docs
weight: 66
url: /cpp/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() method


Returns a list of all slides sections that are defined in the presentation. Read-only [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Remarks


The following examples shows how to create Sections in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 will be ended at newSlide2 and after it section2 will start
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 The following examples shows how to changing the names of Sections. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionCollection](../../isectioncollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)