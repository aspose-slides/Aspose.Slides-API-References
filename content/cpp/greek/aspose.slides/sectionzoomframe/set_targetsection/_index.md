---
title: set_TargetSection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Γράψτε ISection.
type: docs
weight: 14
url: /el/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) μέθοδος


Ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο [Section](../../section/) Zoom. Γράψτε [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Παρατηρήσεις


Το επόμενο παράδειγμα δείχνει την αλλαγή της ενότητας-στόχου και δημιουργεί νέα εικόνα για το αντικείμενο ζουμ ενότητας: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISection](../../isection/)
* Κλάση [SectionZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)