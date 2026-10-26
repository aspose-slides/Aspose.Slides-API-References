---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt ISummaryZoomSectionCollection op voor het Summary Zoom Frame-object.
type: docs
weight: 14
url: /nl/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() methode

Verkrijgt [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) voor het Summary Zoom Frame-object.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Opmerkingen

Het voorbeeld toont het ophalen van Summary Zoom [Section](../../section/) element op basis van index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klasse [SummaryZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)