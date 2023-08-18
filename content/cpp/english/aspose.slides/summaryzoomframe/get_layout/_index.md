---
title: get_Layout()
second_title: Aspose.Slides for C++ API Reference
description: Gets layout of Summary Zoom Sections in the frame. Default value is GridLayout.
type: docs
weight: 1
url: /aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() method


Gets layout of Summary Zoom Sections in the frame. Default value is GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Remarks


The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## See Also

* Enum [ZoomLayout](../../zoomlayout/)
* Class [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)