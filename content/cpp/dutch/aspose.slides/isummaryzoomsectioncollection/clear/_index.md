---
title: Clear()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert alle SummaryZoomSection-objecten uit de collectie.
type: docs
weight: 66
url: /nl/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() methode


Verwijdert alle [SummaryZoomSection](../../summaryzoomsection/) objecten uit de verzameling.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Opmerkingen


Het voorbeeld demonstreert het ophalen van het Summary Zoom [Section](../../section/) element op index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Zie ook

* Klasse [ISummaryZoomSectionCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)