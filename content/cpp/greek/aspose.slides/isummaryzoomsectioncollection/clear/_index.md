---
title: Clear()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή.
type: docs
weight: 66
url: /el/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() μέθοδος

Αφαιρεί όλα τα [SummaryZoomSection](../../summaryzoomsection/) αντικείμενα από τη συλλογή.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Παρατηρήσεις

Το παράδειγμα δείχνει την απόκτηση του στοιχείου Summary Zoom [Section](../../section/) με βάση το ευρετήριο:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Δείτε επίσης

* Κλάση [ISummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)