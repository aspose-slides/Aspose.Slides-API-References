---
title: AddSummaryZoomSection()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή
type: docs
weight: 14
url: /el/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) method


Δημιουργεί νέο αντικείμενο Summary Zoom [Section](../../section/) και το προσθέτει στη συλλογή

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για ένα νέο στοιχείο Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Return Value

Προστέθηκε το στοιχείο [ISummaryZoomFrame](../../isummaryzoomframe/)
## Remarks



Εάν υπάρχει ήδη ένα στοιχείο για αυτήν την ενότητα στη συλλογή, επιστρέφεται το υπάρχον στοιχείο. 

Το παράδειγμα δείχνει την λήψη του στοιχείου Summary Zoom [Section](../../section/) με δείκτη: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)