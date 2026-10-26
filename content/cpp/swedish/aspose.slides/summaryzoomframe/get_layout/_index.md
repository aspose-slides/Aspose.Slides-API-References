---
title: get_Layout()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar layout av Summary Zoom Sections i ramen. Standardvärdet är GridLayout.
type: docs
weight: 1
url: /sv/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() metod


Hämtar layout av Summary Zoom Sections i ramen. Standardvärdet är GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Anmärkningar


Exemplet demonstrerar hur man hämtar Summary Zoom [Section](../../section/) elementet med index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Se också

* Enum [ZoomLayout](../../zoomlayout/)
* Klass [SummaryZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)