---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.
type: docs
weight: 157
url: /aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method


Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the Summary Zoom frame. |
| x | **float** | The x-coordinate of the new Summary Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Summary Zoom frame, in points. |
| width | **float** | The width of the new Summary Zoom frame, in points. |
| height | **float** | The height of the new Summary Zoom frame, in points. |

### Return Value

The newly created [ISummaryZoomFrame](../../isummaryzoomframe/).
## Remarks


This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. 

This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)