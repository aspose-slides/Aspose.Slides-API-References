---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijder Summary Zoom Section object uit de collectie.
type: docs
weight: 40
url: /nl/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) methode

Verwijder Summary Zoom [Section](../../section/) object uit de collectie.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) waarvoor het Summary Zoom [Section](../../section/) element moet worden verwijderd [ISection](../../isection/). |

## Opmerkingen

Het voorbeeld toont het ophalen van Summary Zoom [Section](../../section/) element op index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISection](../../isection/)
* Klasse [ISummaryZoomSectionCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)