---
title: set_Description()
second_title: Aspose.Slides για την αναφορά API C++
description: Επιστρέφει τη λεκτική περιγραφή του αντικειμένου Summary Zoom Section.
type: docs
weight: 40
url: /el/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) μέθοδος

Επιστρέφει τη λεκτική περιγραφή του αντικειμένου Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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