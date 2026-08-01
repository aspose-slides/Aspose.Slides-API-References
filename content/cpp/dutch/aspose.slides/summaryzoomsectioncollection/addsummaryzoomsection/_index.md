---
title: AddSummaryZoomSection()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Summary Zoom Section-object en voegt het toe aan de collectie
type: docs
weight: 53
url: /nl/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) methode


Maakt een nieuw Summary Zoom [Section](../../section/) object aan en voegt het toe aan de collectie

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) voor een nieuw Summary Zoom [Section](../../section/) element [ISection](../../isection/) |

### Retourwaarde

Toegevoegd [ISummaryZoomFrame](../../isummaryzoomframe/) element
## Opmerkingen



Als er al een element voor deze sectie bestaat in de collectie, wordt het bestaande element geretourneerd. 


Het voorbeeld toont het ophalen van een Summary Zoom [Section](../../section/) element op basis van index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)