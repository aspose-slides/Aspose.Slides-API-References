---
title: set_TargetSection()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Section Zoom. Γράψτε ISection.
type: docs
weight: 14
url: /el/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) μέθοδος

Ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο [Section](../../section/) Zoom. Γράψτε [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την αλλαγή της ενότητας-στόχου και δημιουργεί μια νέα εικόνα για το αντικείμενο section zoom:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISection](../../isection/)
* Κλάση [ISectionZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)