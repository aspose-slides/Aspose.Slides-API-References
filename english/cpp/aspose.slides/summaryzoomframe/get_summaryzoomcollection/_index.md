---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API Reference
description: Gets ISummaryZoomSectionCollection for the Summary Zoom Frame object.
type: docs
weight: 14
url: /cpp/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() method


Gets [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) for the Summary Zoom Frame object.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Remarks


The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Class [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
