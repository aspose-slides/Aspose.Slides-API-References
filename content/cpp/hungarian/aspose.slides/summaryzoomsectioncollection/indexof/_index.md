---
title: IndexOf()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott SummaryZoomSection objektum indexét.
type: docs
weight: 66
url: /hu/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metódus

Visszaadja a megadott [SummaryZoomSection](../../summaryzoomsection/) objektum indexét.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objektum a [ISummaryZoomSection](../../isummaryzoomsection/) megtalálásához. |

### Visszatérési érték

[SummaryZoomSection](../../summaryzoomsection/) objektum indexe vagy -1, ha a [SummaryZoomSection](../../summaryzoomsection/) objektum nem ebben a gyűjteményben van.

## Megjegyzések



A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom [Section](../../section/) elemet: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomSection](../../isummaryzoomsection/)
* Osztály [SummaryZoomSectionCollection](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)