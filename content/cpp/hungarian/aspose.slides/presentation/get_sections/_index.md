---
title: get_Sections()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a prezentációban definiált összes dia szakasz listáját. Csak olvasható ISectionCollection.
type: docs
weight: 66
url: /hu/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() metódus


Visszaadja a prezentációban definiált összes diák szakasz listáját. Csak olvasható [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Megjegyzések


Az alábbi példák bemutatják, hogyan hozhatók létre Szakaszok egy PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 befejeződik a newSlide2-nél, és utána a section2 kezdődik
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Az alábbi példák bemutatják, hogyan lehet megváltoztatni a Szakaszok nevét.
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISectionCollection](../../isectioncollection/)
* Osztály [Presentation](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)