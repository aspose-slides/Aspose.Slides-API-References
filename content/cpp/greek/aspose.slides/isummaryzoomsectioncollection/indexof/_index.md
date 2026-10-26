---
title: IndexOf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει έναν δείκτη του συγκεκριμένου αντικειμένου SummaryZoomSection.
type: docs
weight: 53
url: /el/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) μέθοδος

Επιστρέφει έναν δείκτη του συγκεκριμένου αντικειμένου [SummaryZoomSection](../../summaryzoomsection/).

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) αντικείμενο για να βρεθεί [ISummaryZoomSection](../../isummaryzoomsection/). |

### Τιμή Επιστροφής

Δείκτης ενός αντικειμένου [SummaryZoomSection](../../summaryzoomsection/) ή -1 εάν το αντικείμενο [SummaryZoomSection](../../summaryzoomsection/) δεν προέρχεται από αυτή τη συλλογή.

## Παρατηρήσεις

Το παράδειγμα δείχνει την απόκτηση του στοιχείου Summary Zoom [Section](../../section/) με χρήση δείκτη:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomSection](../../isummaryzoomsection/)
* Κλάση [ISummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)