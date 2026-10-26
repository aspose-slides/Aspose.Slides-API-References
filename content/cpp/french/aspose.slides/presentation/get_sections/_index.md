---
title: get_Sections()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une liste de toutes les sections de diapositives qui sont définies dans la présentation. Lecture seule ISectionCollection.
type: docs
weight: 66
url: /fr/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() méthode


Renvoie une liste de toutes les sections de diapositives qui sont définies dans la présentation. Lecture seule [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Remarques


 Les exemples suivants montrent comment créer des Sections dans un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 sera terminée à newSlide2 et après, section2 commencera
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Les exemples suivants montrent comment modifier les noms des Sections. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISectionCollection](../../isectioncollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)