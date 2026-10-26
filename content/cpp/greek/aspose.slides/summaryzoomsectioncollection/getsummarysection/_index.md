---
title: GetSummarySection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το στοιχείο Summary Zoom Section για το δεδομένο τμήμα.
type: docs
weight: 92
url: /el/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) μέθοδος

Επιστρέφει το στοιχείο Summary Zoom [Section](../../section/) για το συγκεκριμένο τμήμα.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για να βρείτε [ISection](../../isection/) |

### Τιμή Επιστροφής

[ISummaryZoomSection](../../isummaryzoomsection/) ή null αν η συλλογή δεν περιέχει στοιχείο για το τμήμα.

## Παρατηρήσεις

Το παράδειγμα δείχνει την απόκτηση του στοιχείου Summary Zoom [Section](../../section/) με βάση το δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)