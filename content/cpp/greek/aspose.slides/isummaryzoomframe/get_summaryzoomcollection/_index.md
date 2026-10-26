---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποκτά ISummaryZoomSectionCollection για το αντικείμενο Summary Zoom Frame.
type: docs
weight: 14
url: /el/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() μέθοδος


Αποκτά [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) για το αντικείμενο Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Παρατηρήσεις


Το παράδειγμα δείχνει τη λήψη του στοιχείου Summary Zoom [Section](../../section/) με δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Κλάση [ISummaryZoomFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)