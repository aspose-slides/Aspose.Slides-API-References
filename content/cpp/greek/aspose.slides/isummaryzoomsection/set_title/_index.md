---
title: set_Title()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει τον κειμενικό τίτλο του αντικειμένου Summary Zoom Section.
type: docs
weight: 14
url: /el/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) μέθοδος


Επιστρέφει τον κειμενικό τίτλο του αντικειμένου Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
```

## Σχόλια


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