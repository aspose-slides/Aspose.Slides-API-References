---
title: GetSummarySection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το στοιχείο Summary Zoom Section για τη δεδομένη ενότητα.
type: docs
weight: 27
url: /el/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) μέθοδος


Επιστρέφει το στοιχείο Summary Zoom [Section](../../section/) για την δοθείσα ενότητα.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για να βρεθεί [ISection](../../isection/) |

### Τιμή Επιστροφής

[ISummaryZoomSection](../../isummaryzoomsection/) ή null εάν η συλλογή δεν περιέχει στοιχείο για την ενότητα.
## Σχόλια



Το παράδειγμα δείχνει την λήψη του στοιχείου Summary Zoom [Section](../../section/) με βάση τον δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomSection](../../isummaryzoomsection/)
* Κλάση [ISection](../../isection/)
* Κλάση [ISummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)