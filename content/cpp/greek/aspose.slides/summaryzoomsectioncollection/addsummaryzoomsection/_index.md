---
title: AddSummaryZoomSection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή
type: docs
weight: 53
url: /el/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) μέθοδος

Δημιουργεί νέο Summary Zoom [Section](../../section/) αντικείμενο και το προσθέτει στη συλλογή

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για ένα νέο Summary Zoom [Section](../../section/) στοιχείο [ISection](../../isection/) |

### Τιμή Επιστροφής

Προστέθηκε [ISummaryZoomFrame](../../isummaryzoomframe/) στοιχείο

## Σχόλια

Εάν υπάρχει ήδη ένα στοιχείο για αυτήν την ενότητα στη συλλογή, επιστρέφεται το υπάρχον στοιχείο.

Το παράδειγμα δείχνει την λήψη του Summary Zoom [Section](../../section/) στοιχείου με δείκτη:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISummaryZoomSection](../../isummaryzoomsection/)
* Κλάση [ISection](../../isection/)
* Κλάση [SummaryZoomSectionCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)