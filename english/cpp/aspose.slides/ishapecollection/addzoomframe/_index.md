---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new Zoom object to the end of a collection.
type: docs
weight: 92
url: /cpp/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method


Adds a new Zoom object to the end of a collection.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new Zoom frame **float**. |
| y | **float** | Y coordinate of a new Zoom frame **float**. |
| width | **float** | Width of a new Zoom frame **float**. |
| height | **float** | Height of a new Zoom frame **float**. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The slide object referenced by the Zoom frame [ISlide](../../islide/). |

### Return Value

Created Zoom object [IZoomFrame](../../izoomframe/).
## Remarks


This example demonstrates adding a Zoom object to the end of a collection (assume that there are at least two slides in the \"Presentation.pptx\" presentation): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method


Adds a new Zoom object to the end of a collection.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new Zoom frame **float**. |
| y | **float** | Y coordinate of a new Zoom frame **float**. |
| width | **float** | Width of a new Zoom frame **float**. |
| height | **float** | Height of a new Zoom frame **float**. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The slide object referenced by the Zoom frame [ISlide](../../islide/). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image for the referenced slide [IPPImage](../../ippimage/) |

### Return Value

Created Zoom object [IZoomFrame](../../izoomframe/).
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