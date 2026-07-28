---
title: GetSummarySection()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja az adott szakaszhoz tartozó Summary Zoom Section elemet.
type: docs
weight: 27
url: /hu/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metódus

Visszaadja a megadott szakaszhoz tartozó Summary Zoom [Section](../../section/) elemet.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) a [ISection](../../isection/) megtalálásához |

### Visszatérési érték

[ISummaryZoomSection](../../isummaryzoomsection/) vagy null, ha a gyűjtemény nem tartalmaz elemet a szakaszhoz.

## Megjegyzések

A példa bemutatja a Summary Zoom [Section](../../section/) elem index alapján történő lekérését: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomSection](../../isummaryzoomsection/)
* Osztály [ISection](../../isection/)
* Osztály [ISummaryZoomSectionCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)