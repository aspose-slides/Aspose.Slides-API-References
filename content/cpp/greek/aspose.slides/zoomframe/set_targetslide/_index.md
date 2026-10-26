---
title: set_TargetSlide()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει το αντικείμενο διαφάνειας στο οποίο το αντικείμενο Slide Zoom συνδέεται. Γράψτε ISlide.
type: docs
weight: 14
url: /el/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) μέθοδος

Ορίζει το αντικείμενο διαφάνειας στο οποίο το αντικείμενο [Slide](../../slide/) Zoom συνδέεται. Γράψτε [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Σχόλια

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
* Βιβλιοθήκη [Aspose.Slides](../../../)