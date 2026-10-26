---
title: GetSummarySection()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert Summary Zoom Section element voor de opgegeven sectie.
type: docs
weight: 27
url: /nl/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) methode

Retourneert Summary Zoom [Section](../../section/) element voor de opgegeven sectie.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) om [ISection](../../isection/) te vinden |

### Retourwaarde

[ISummaryZoomSection](../../isummaryzoomsection/) of null als de collectie geen element bevat voor de sectie.

## Opmerkingen

Het voorbeeld laat zien hoe je het Summary Zoom [Section](../../section/) element op index haalt:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [ISection](../../isection/)
* Klasse [ISummaryZoomSectionCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)