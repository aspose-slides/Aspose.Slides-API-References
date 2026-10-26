---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt ISummaryZoomSectionCollection op voor het Summary Zoom Frame object.
type: docs
weight: 14
url: /nl/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() methode


Haalt [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) op voor het Summary Zoom Frame object.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Opmerkingen


Het voorbeeld toont het ophalen van het Summary Zoom [Section](../../section/) element op index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klasse [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)