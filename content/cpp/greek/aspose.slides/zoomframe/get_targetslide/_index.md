---
title: get_TargetSlide()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο Slide Zoom. Διαβάστε ISlide.
type: docs
weight: 1
url: /el/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() μέθοδος

Λαμβάνει το αντικείμενο διαφάνειας στο οποίο συνδέεται το αντικείμενο [Slide](../../slide/) Zoom. Διαβάστε [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Παρατηρήσεις

Το επόμενο παράδειγμα δείχνει την αλλαγή της διαφάνειας-στόχου και δημιουργεί νέα εικόνα για το αντικείμενο [Slide](../../slide/) Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [ZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)