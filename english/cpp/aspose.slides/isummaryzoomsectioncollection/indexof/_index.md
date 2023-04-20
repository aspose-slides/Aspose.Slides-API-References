---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Returns an index of the specified SummaryZoomSection object.
type: docs
weight: 53
url: /cpp/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) method


Returns an index of the specified [SummaryZoomSection](../../summaryzoomsection/) object.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) object to find [ISummaryZoomSection](../../isummaryzoomsection/). |

### Return Value

Index of a [SummaryZoomSection](../../summaryzoomsection/) object or -1 if [SummaryZoomSection](../../summaryzoomsection/) object not from this collection.
## Remarks



The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)