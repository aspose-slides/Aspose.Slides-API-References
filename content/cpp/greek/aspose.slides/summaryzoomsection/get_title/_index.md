---
title: get_Title()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει τον κειμενικό τίτλο του αντικειμένου Summary Zoom Section.
type: docs
weight: 1
url: /el/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() μέθοδος

Επιστρέφει τον κειμενικό τίτλο του αντικειμένου Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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
* Κλάση [SummaryZoomSection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)