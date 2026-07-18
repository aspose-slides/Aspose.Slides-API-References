---
title: IndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει έναν δείκτη του καθορισμένου αντικειμένου SummaryZoomSection.
type: docs
weight: 66
url: /el/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) μέθοδος

Επιστρέφει ένα δείκτη του καθορισμένου [SummaryZoomSection](../../summaryzoomsection/) αντικειμένου.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | Αντικείμενο [SummaryZoomSection](../../summaryzoomsection/) για την εύρεση του [ISummaryZoomSection](../../isummaryzoomsection/). |

### Τιμή Επιστροφής

Δείκτης ενός [SummaryZoomSection](../../summaryzoomsection/) αντικειμένου ή -1 αν το [SummaryZoomSection](../../summaryzoomsection/) αντικείμενο δεν προέρχεται από αυτή τη συλλογή.

## Παρατηρήσεις

Το παράδειγμα δείχνει την λήψη του στοιχείου Summary Zoom [Section](../../section/) με δείκτη: 
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
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)