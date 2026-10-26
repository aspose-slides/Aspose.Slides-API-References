---
title: set_Description()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την περιγραφή κειμένου του αντικειμένου Summary Zoom Section.
type: docs
weight: 40
url: /el/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) μέθοδος


Επιστρέφει την περιγραφή κειμένου του Summary Zoom [Section](../../section/) αντικειμένου.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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
* Κλάση [SummaryZoomSection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)