---
title: get_Layout()
second_title: Aspose.Slides voor C++ API-referentie
description: Verkrijgt de lay-out van Summary Zoom-secties in het frame. Standaardwaarde is GridLayout.
type: docs
weight: 1
url: /nl/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() methode


Verkrijgt de lay-out van Summary Zoom-secties in het frame. Standaardwaarde is GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Opmerkingen


Het voorbeeld demonstreert het ophalen van het Summary Zoom [Section](../../section/) element op basis van een index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Zie ook

* Enum [ZoomLayout](../../zoomlayout/)
* Klasse [SummaryZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)