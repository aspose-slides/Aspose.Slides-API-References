---
title: AddSummaryZoomSection()
second_title: Aspose.Slides C++ API Referencia
description: Új Summary Zoom Section objektumot hoz létre, és hozzáadja a gyűjteményhez
type: docs
weight: 53
url: /hu/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metódus

Új Summary Zoom [Section](../../section/) objektumot hoz létre, és hozzáadja a gyűjteményhez

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) egy új Summary Zoom [Section](../../section/) elemhez [ISection](../../isection/) |

### Visszatérési érték

Hozzáadott [ISummaryZoomFrame](../../isummaryzoomframe/) elem

## Megjegyzések

Ha már létezik egy elem ehhez a szakaszhoz a gyűjteményben, a meglévő elem kerül visszaadásra.

A példa bemutatja, hogyan lehet a Summary Zoom [Section](../../section/) elemet index alapján lekérni: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISummaryZoomSection](../../isummaryzoomsection/)
* Osztály [ISection](../../isection/)
* Osztály [SummaryZoomSectionCollection](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)