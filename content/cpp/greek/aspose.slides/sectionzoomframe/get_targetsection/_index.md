---
title: get_TargetSection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Διαβάστε ISection.
type: docs
weight: 1
url: /el/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() μέθοδος

Λαμβάνει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο [Section](../../section/) Zoom. Διαβάστε [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Παρατηρήσεις

Το επόμενο παράδειγμα δείχνει την αλλαγή της ενότητας-στόχου και δημιουργεί νέα εικόνα για το αντικείμενο section zoom:

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
* Βιβλιοθήκη [Aspose.Slides](../../../)