---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new Summary Zoom object to the end of a collection.
type: docs
weight: 144
url: /aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) method


Adds a new Summary Zoom object to the end of a collection.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new [Section](../../section/) Zoom frame **float**. |
| y | **float** | Y coordinate of a new [Section](../../section/) Zoom frame **float**. |
| width | **float** | Width of a new [Section](../../section/) Zoom frame **float**. |
| height | **float** | Height of a new [Section](../../section/) Zoom frame **float**. |

### Return Value

Created Summary Zoom object [ISummaryZoomFrame](../../isummaryzoomframe/).
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
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)