---
title: get_Layout()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τη διάταξη των τμημάτων Summary Zoom στο πλαίσιο. Η προεπιλεγμένη τιμή είναι GridLayout.
type: docs
weight: 1
url: /el/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() μέθοδος


Λαμβάνει τη διάταξη των τμημάτων Summary Zoom στο πλαίσιο. Η προεπιλεγμένη τιμή είναι GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Παρατηρήσεις


Το παράδειγμα δείχνει πώς να λαμβάνεται το στοιχείο Summary Zoom [Section](../../section/) με δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Δείτε επίσης

* Απαρίθμηση [ZoomLayout](../../zoomlayout/)
* Κλάση [ISummaryZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)