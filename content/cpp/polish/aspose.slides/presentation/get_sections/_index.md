---
title: get_Sections()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca listę wszystkich sekcji slajdów, które są zdefiniowane w prezentacji. Tylko do odczytu ISectionCollection.
type: docs
weight: 66
url: /pl/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() metoda


Zwraca listę wszystkich sekcji slajdów, które są zdefiniowane w prezentacji. Tylko do odczytu [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Uwagi


Poniższe przykłady pokazują, jak utworzyć sekcje w programie PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 zostanie zakończony w newSlide2, a po nim zacznie się section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Poniższe przykłady pokazują, jak zmienić nazwy sekcji. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISectionCollection](../../isectioncollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)