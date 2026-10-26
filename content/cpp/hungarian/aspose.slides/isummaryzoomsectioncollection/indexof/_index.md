---
title: IndexOf()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott SummaryZoomSection objektum indexét.
type: docs
weight: 53
url: /hu/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metódus

Visszaad egy indexet a megadott [SummaryZoomSection](../../summaryzoomsection/) objektumról.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objektum a(z) [ISummaryZoomSection](../../isummaryzoomsection/) megtalálásához. |

### Visszatérési érték

[SummaryZoomSection](../../summaryzoomsection/) objektum indexe, vagy -1, ha a(z) [SummaryZoomSection](../../summaryzoomsection/) objektum nem ebben a gyűjteményben van.

## Megjegyzések

A példában a Summary Zoom [Section](../../section/) elem index szerinti lekérését mutatja be:
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
* Osztály [ISummaryZoomSectionCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)