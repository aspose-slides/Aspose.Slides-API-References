---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρέστε το αντικείμενο Summary Zoom Section από τη συλλογή.
type: docs
weight: 40
url: /el/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) μέθοδος

Αφαιρέστε το αντικείμενο Summary Zoom [Section](../../section/) από τη συλλογή.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για το οποίο το στοιχείο Summary Zoom [Section](../../section/) πρέπει να αφαιρεθεί [ISection](../../isection/). |

## Σχόλια

Το παράδειγμα δείχνει τη λήψη του στοιχείου Summary Zoom [Section](../../section/) με βάση το δείκτη:
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
* Κλάση [ISummaryZoomSectionCollection](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)