---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει ISummaryZoomSectionCollection για το αντικείμενο Summary Zoom Frame.
type: docs
weight: 14
url: /el/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() μέθοδος

Λαμβάνει [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) για το αντικείμενο Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Παρατηρήσεις

Το παράδειγμα δείχνει την λήψη του στοιχείου Summary Zoom [Section](../../section/) με δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Κλάση [SummaryZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)