---
title: Clear()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert alle SummaryZoomSection-objecten uit de collectie.
type: docs
weight: 105
url: /nl/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() methode

Verwijdert alle [SummaryZoomSection](../../summaryzoomsection/) objecten uit de collectie.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Opmerkingen

Het voorbeeld toont het ophalen van het Summary Zoom [Section](../../section/) element op basis van index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Zie ook

* Klasse [SummaryZoomSectionCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)