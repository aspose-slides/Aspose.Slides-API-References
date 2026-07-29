---
title: get_Sections()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en lista med alla bildavsnitt som är definierade i presentationen. Skrivskyddad ISectionCollection.
type: docs
weight: 66
url: /sv/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() metod


Returnerar en lista med alla bildavsnitt som är definierade i presentationen. Skrivskyddad [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Anmärkningar


Följande exempel visar hur man skapar Sections i en PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 kommer att avslutas vid newSlide2 och efter den börjar section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Följande exempel visar hur man ändrar namnen på Sections. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISectionCollection](../../isectioncollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)