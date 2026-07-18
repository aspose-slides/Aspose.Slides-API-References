---
title: get_Layout()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τη διάταξη των Summary Zoom Sections στο πλαίσιο. Η προεπιλεγμένη τιμή είναι GridLayout.
type: docs
weight: 1
url: /el/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() μέθοδος

Λαμβάνει τη διάταξη των Summary Zoom Sections στο πλαίσιο. Η προεπιλεγμένη τιμή είναι GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Σχόλια

Το παράδειγμα δείχνει την λήψη του στοιχείου Summary Zoom [Section](../../section/) με δείκτη:

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Δείτε επίσης

* Απαρίθμηση [ZoomLayout](../../zoomlayout/)
* Κλάση [SummaryZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)