---
title: get_Sections()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een lijst van alle dia secties die zijn gedefinieerd in de presentatie. Alleen-lezen ISectionCollection.
type: docs
weight: 66
url: /nl/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() methode


Retourneert een lijst van alle dia secties die zijn gedefinieerd in de presentatie. Alleen-lezen [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Opmerkingen


De volgende voorbeelden laten zien hoe secties te maken in een PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 zal worden beëindigd bij newSlide2 en daarna zal section2 starten
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 De volgende voorbeelden laten zien hoe de namen van secties te wijzigen. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISectionCollection](../../isectioncollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)