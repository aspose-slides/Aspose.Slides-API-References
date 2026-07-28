---
title: get_Layout()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri a Summary Zoom szakaszok elrendezését a képkockában. Alapértelmezett érték a GridLayout.
type: docs
weight: 1
url: /hu/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() metódus


A képkockában a Summary Zoom Sections elrendezését kapja meg. Alapértelmezett érték a GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Megjegyzések


A példa bemutatja a Summary Zoom [Section](../../section/) elem index szerinti lekérését:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Lásd még

* Enum [ZoomLayout](../../zoomlayout/)
* Osztály [SummaryZoomFrame](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)