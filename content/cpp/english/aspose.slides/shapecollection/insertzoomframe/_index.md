---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Zoom frame and inserts it into the shape collection at the specified index.
type: docs
weight: 118
url: /aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method


Creates a new Zoom frame and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the Zoom frame. |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The [ISlide](../../islide/) referenced by the Zoom frame. |

### Return Value

The newly created [IZoomFrame](../../izoomframe/).
## Remarks


This example demonstrates creation and inserting a Zoom object at the specified index of a collection (assume that there are at least two slides in the \"Presentation.pptx\" presentation): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method


Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the Zoom frame. |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The [ISlide](../../islide/) referenced by the Zoom frame. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image for the referenced slide [IPPImage](../../ippimage/). |

### Return Value

The newly created [IZoomFrame](../../izoomframe/).
## Remarks


This example demonstrates creation and inserting a Zoom object at the specified index of a collection (assume that there are at least two slides in the \"Presentation.pptx\" presentation): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)