---
title: get_Description()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την περιγραφή κειμένου του αντικειμένου Summary Zoom Section.
type: docs
weight: 27
url: /el/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() μέθοδος

Επιστρέφει την περιγραφή κειμένου του αντικειμένου Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ISummaryZoomSection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)