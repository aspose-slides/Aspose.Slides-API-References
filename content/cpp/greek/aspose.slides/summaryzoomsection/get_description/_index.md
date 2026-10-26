---
title: get_Description()
second_title: Aspose.Slides για C++ αναφορά API
description: Επιστρέφει την περιγραφή κειμένου του αντικειμένου Summary Zoom Section.
type: docs
weight: 27
url: /el/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() μέθοδος

Επιστρέφει την περιγραφή κειμένου του αντικειμένου Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
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