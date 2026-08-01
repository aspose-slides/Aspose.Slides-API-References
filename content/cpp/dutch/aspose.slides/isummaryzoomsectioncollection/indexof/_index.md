---
title: IndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een index van het opgegeven SummaryZoomSection object.
type: docs
weight: 53
url: /nl/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) methode

Retourneert een index van het opgegeven [SummaryZoomSection](../../summaryzoomsection/) object.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) object om [ISummaryZoomSection](../../isummaryzoomsection/) te vinden. |

### Retourwaarde

Index van een [SummaryZoomSection](../../summaryzoomsection/) object of -1 als het [SummaryZoomSection](../../summaryzoomsection/) object niet uit deze collectie komt.

## Opmerkingen

Het voorbeeld toont het ophalen van Summary Zoom [Section](../../section/) element op basis van een index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)