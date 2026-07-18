---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρέστε το αντικείμενο Summary Zoom Section από τη συλλογή.
type: docs
weight: 79
url: /el/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) μέθοδος

Αφαιρέστε το αντικείμενο Summary Zoom [Section](../../section/) από τη συλλογή.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για το οποίο το στοιχείο Summary Zoom [Section](../../section/) πρέπει να αφαιρεθεί [ISection](../../isection/). |

## Παρατηρήσεις

Το παράδειγμα δείχνει την λήψη του στοιχείου Summary Zoom [Section](../../section/) με βάση τον δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISection](../../isection/)
* Κλάση [SummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)