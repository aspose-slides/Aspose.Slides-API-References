---
title: set_TargetSlide()
second_title: Aspose.Slides για την αναφορά API του C++
description: Ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom. Γράψτε ISlide.
type: docs
weight: 14
url: /el/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) μέθοδος

Ορίζει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Zoom [Slide](../../slide/). Γράψτε [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Παρατηρήσεις

Το επόμενο παράδειγμα δείχνει την αλλαγή της διαφάνειας-στόχου και δημιουργεί νέα εικόνα για το αντικείμενο Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [IZoomFrame](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)