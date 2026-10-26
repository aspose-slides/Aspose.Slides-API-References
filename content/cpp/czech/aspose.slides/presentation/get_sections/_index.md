---
title: get_Sections()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací seznam všech sekcí snímků, které jsou v prezentaci definovány. Pouze pro čtení ISectionCollection.
type: docs
weight: 66
url: /cs/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() metoda


Vrací seznam všech sekcí snímků, které jsou v prezentaci definovány. Pouze pro čtení [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Poznámky


Následující příklady ukazují, jak vytvořit sekce v PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 bude ukončena na newSlide2 a po ní začne section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Následující příklady ukazují, jak měnit názvy sekcí. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISectionCollection](../../isectioncollection/)
* Třída [Presentation](../)
* Prostor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)