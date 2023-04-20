---
title: get_Layout()
second_title: Aspose.Slides for C++ API Reference
description: Gets layout of Summary Zoom Sections in the frame. Default value is GridLayout.
type: docs
weight: 1
url: /cpp/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() method


Gets layout of Summary Zoom Sections in the frame. Default value is GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
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
* Class [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)