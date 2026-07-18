---
title: get_Title()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Επιστρέφει τον τίτλο κειμένου του αντικειμένου Summary Zoom Section.
type: docs
weight: 1
url: /el/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() μέθοδος

Επιστρέφει τον τίτλο κειμένου του αντικειμένου Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ISummaryZoomSection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)