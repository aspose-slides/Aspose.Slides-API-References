---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Summary Zoom frame and adds it to the end of the shape collection.
type: docs
weight: 157
url: /aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) method


Creates a new Summary Zoom frame and adds it to the end of the shape collection.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new Summary Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Summary Zoom frame, in points. |
| width | **float** | The width of the new Summary Zoom frame, in points. |
| height | **float** | The height of the new Summary Zoom frame, in points. |

### Return Value

The newly created [ISummaryZoomFrame](../../isummaryzoomframe/).
## Remarks


This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. 

This example demonstrates adding a Summary Zoom object to the end of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)