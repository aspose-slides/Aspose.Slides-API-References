---
title: get_Layout()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar layouten för Summary Zoom-sektioner i ramen. Standardvärdet är GridLayout.
type: docs
weight: 1
url: /sv/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() metod


Hämtar layouten för Summary Zoom-sektioner i ramen. Standardvärdet är GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Anmärkningar


Exemplet demonstrerar hur man hämtar Summary Zoom [Section](../../section/) elementet med index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Se även

* Enum [ZoomLayout](../../zoomlayout/)
* Klass [ISummaryZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)