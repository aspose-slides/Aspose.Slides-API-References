---
title: Clear()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καταργεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή.
type: docs
weight: 105
url: /el/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() μέθοδος


Καταργεί όλα τα [SummaryZoomSection](../../summaryzoomsection/) αντικείμενα από τη συλλογή.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Παρατηρήσεις


Το παράδειγμα δείχνει τη λήψη του στοιχείου Summary Zoom [Section](../../section/) με δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Δείτε επίσης

* Κλάση [SummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)