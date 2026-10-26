---
title: get_TargetSlide()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει το αντικείμενο διαφάνειας στο οποίο το Slide Zoom αντικείμενο συνδέεται. Διαβάστε ISlide.
type: docs
weight: 1
url: /el/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() μέθοδος

Λαμβάνει το αντικείμενο διαφάνειας στο οποίο το [Slide](../../slide/) Zoom αντικείμενο συνδέεται. Διαβάστε [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Παρατηρήσεις

Το επόμενο παράδειγμα δείχνει την αλλαγή της διαφάνειας-στόχου και δημιουργεί νέα εικόνα για το [Slide](../../slide/) Zoom αντικείμενο:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [IZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)