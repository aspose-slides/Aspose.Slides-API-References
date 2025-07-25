---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Section Zoom frame and adds it to the end of the shape collection.
type: docs
weight: 118
url: /aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method


Creates a new [Section](../../section/) Zoom frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| y | **float** | The y-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| width | **float** | The width of the new [Section](../../section/) Zoom frame, in points. |
| height | **float** | The height of the new [Section](../../section/) Zoom frame, in points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The [ISection](../../isection/) referenced by the [Section](../../section/) Zoom frame; must belong to this presentation and contain at least one slide. |

### Return Value

The newly created [ISectionZoomFrame](../../isectionzoomframe/).
## Remarks


This example demonstrates adding a [Section](../../section/) Zoom object to the end of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Creates a new [Section](../../section/) Zoom frame with a predefined image and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| y | **float** | The y-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| width | **float** | The width of the new [Section](../../section/) Zoom frame, in points. |
| height | **float** | The height of the new [Section](../../section/) Zoom frame, in points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The [ISection](../../isection/) referenced by the [Section](../../section/) Zoom frame; must belong to this presentation and contain at least one slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The [IPPImage](../../ippimage/) to display within the [Section](../../section/) Zoom frame. |

### Return Value

The newly created [ISectionZoomFrame](../../isectionzoomframe/).
## Remarks


This example demonstrates adding a [Section](../../section/) Zoom object to the end of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)