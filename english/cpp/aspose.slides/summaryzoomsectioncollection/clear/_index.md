---
title: Clear()
second_title: Aspose.Slides for C++ API Reference
description: Removes all SummaryZoomSection objects from the collection.
type: docs
weight: 105
url: /cpp/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() method


Removes all [SummaryZoomSection](../../summaryzoomsection/) objects from the collection.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Remarks


The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## See Also

* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
