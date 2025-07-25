---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Zoom frame and adds it to the end of the shape collection.
type: docs
weight: 92
url: /aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method


Creates a new Zoom frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The [ISlide](../../islide/) referenced by the Zoom frame; must belong to this presentation. |

### Return Value

The newly created [IZoomFrame](../../izoomframe/).
## Remarks


This example demonstrates adding a Zoom object to the end of a collection (assume that there are at least two slides in the \"Presentation.pptx\" presentation): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method


Creates a new Zoom frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The [ISlide](../../islide/) referenced by the Zoom frame; must belong to this presentation. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image for the referenced slide [IPPImage](../../ippimage/). |

### Return Value

The newly created [IZoomFrame](../../izoomframe/).
## Remarks


This example demonstrates adding a Zoom object to the end of a collection (assume that there are at least two slides in the \"Presentation.pptx\" presentation): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)