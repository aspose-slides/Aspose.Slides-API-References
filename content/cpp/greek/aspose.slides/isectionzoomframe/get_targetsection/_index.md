---
title: get_TargetSection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει το αντικείμενο της ενότητας στο οποίο είναι συνδεδεμένο το αντικείμενο Section Zoom. Διαβάστε ISection.
type: docs
weight: 1
url: /el/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() μέθοδος

Λαμβάνει το αντικείμενο της ενότητας στο οποίο το αντικείμενο Zoom [Section](../../section/) είναι συνδεδεμένο. Διαβάστε [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την αλλαγή της ενότητας-στόχου και δημιουργεί μια νέα εικόνα για το αντικείμενο zoom της ενότητας: 
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
* Library [Aspose.Slides](../../../)