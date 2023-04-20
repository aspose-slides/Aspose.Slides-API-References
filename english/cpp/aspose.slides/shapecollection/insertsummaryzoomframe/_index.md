---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Summary Zoom object and inserts it to a collection at the specified index.
type: docs
weight: 170
url: /cpp/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method


Creates a new Summary Zoom object and inserts it to a collection at the specified index.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which [Section](../../section/) Zoom frame should be inserted. |
| x | **float** | X coordinate of a new [Section](../../section/) Zoom frame **float**. |
| y | **float** | Y coordinate of a new [Section](../../section/) Zoom frame **float**. |
| width | **float** | Width of a new [Section](../../section/) Zoom frame **float**. |
| height | **float** | Height of a new [Section](../../section/) Zoom frame **float**. |

### Return Value

Created Summary Zoom object [ISummaryZoomFrame](../../isummaryzoomframe/).
## Remarks


This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. 

This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)