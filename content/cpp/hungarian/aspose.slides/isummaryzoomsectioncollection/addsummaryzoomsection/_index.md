---
title: AddSummaryZoomSection()
second_title: Aspose.Slides C++ API referenciája
description: Új Summary Zoom Section objektumot hoz létre, és hozzáadja a gyűjteményhez
type: docs
weight: 14
url: /hu/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metódus

Új Summary Zoom [Section](../../section/) objektumot hoz létre, és hozzáadja a gyűjteményhez

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) for a new Summary Zoom [Section](../../section/) element [ISection](../../isection/) |

### Visszatérési érték

Hozzáadott [ISummaryZoomFrame](../../isummaryzoomframe/) elem

## Megjegyzés



Ha egy elem már létezik ebben a szakaszban a gyűjteményben, a meglévő elem kerül visszaadva.

A példa bemutatja, hogyan lehet index szerint lekérni a Summary Zoom [Section](../../section/) elemet: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [ISummaryZoomSection](../../isummaryzoomsection/)
* osztály [ISection](../../isection/)
* osztály [ISummaryZoomSectionCollection](../)
* névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)