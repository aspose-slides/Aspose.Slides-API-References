---
title: get_Sections()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un elenco di tutte le sezioni delle diapositive che sono definite nella presentazione. Sola lettura ISectionCollection.
type: docs
weight: 66
url: /it/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() metodo


Restituisce un elenco di tutte le sezioni delle diapositive che sono definite nella presentazione. Sola lettura [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Osservazioni


Gli esempi seguenti mostrano come creare sezioni in un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 terminerà a newSlide2 e dopo di esso section2 inizierà
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Gli esempi seguenti mostrano come modificare i nomi delle sezioni. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISectionCollection](../../isectioncollection/)
* Classe [Presentation](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)