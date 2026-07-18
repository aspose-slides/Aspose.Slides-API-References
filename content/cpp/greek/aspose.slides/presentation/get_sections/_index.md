---
title: get_Sections()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει μια λίστα με όλες τις ενότητες διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση ISectionCollection.
type: docs
weight: 66
url: /el/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() μέθοδος

Επιστρέφει μια λίστα με όλες τις ενότητες διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Παρατηρήσεις


Τα παρακάτω παραδείγματα δείχνουν πώς να δημιουργήσετε Ενότητες σε ένα PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 θα λήξει στο newSlide2 και μετά από αυτό θα ξεκινήσει το section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Τα παρακάτω παραδείγματα δείχνουν πώς να αλλάξετε τα ονόματα των Ενοτήτων. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISectionCollection](../../isectioncollection/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)