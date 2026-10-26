---
title: get_Layout()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de lay-out op van Summary Zoom-secties in het frame. Standaardwaarde is GridLayout.
type: docs
weight: 1
url: /nl/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() methode


Haalt de lay-out op van Summary Zoom-secties in het frame. Standaardwaarde is GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Opmerkingen


Het voorbeeld toont het ophalen van Summary Zoom [Section](../../section/) element op index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Zie ook

* Enum [ZoomLayout](../../zoomlayout/)
* Klasse [ISummaryZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)