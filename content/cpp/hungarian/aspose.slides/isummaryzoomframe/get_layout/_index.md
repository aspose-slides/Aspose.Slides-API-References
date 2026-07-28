---
title: get_Layout()
second_title: Aspose.Slides C++ API referencia
description: Megkapja a Summary Zoom szakaszok elrendezését a keretben. Alapértelmezett érték a GridLayout.
type: docs
weight: 1
url: /hu/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() metódus


Megkapja a Summary Zoom szakaszok elrendezését a keretben. Alapértelmezett érték a GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Megjegyzések


A példa bemutatja a Summary Zoom [Section](../../section/) elem lekérését index alapján: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Lásd még

* Enum [ZoomLayout](../../zoomlayout/)
* Osztály [ISummaryZoomFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)