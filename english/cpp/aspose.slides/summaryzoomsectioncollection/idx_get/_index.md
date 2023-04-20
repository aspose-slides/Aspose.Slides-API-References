---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Gets the element at the specified index. Read-only ISummaryZoomSection.
type: docs
weight: 40
url: /cpp/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) method


Gets the element at the specified index. Read-only [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Remarks


The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)