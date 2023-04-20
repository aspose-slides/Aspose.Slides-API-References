---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new Section Zoom object to the end of a collection.
type: docs
weight: 131
url: /cpp/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method


Adds a new [Section](../../section/) Zoom object to the end of a collection.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new [Section](../../section/) Zoom frame **float**. |
| y | **float** | Y coordinate of a new [Section](../../section/) Zoom frame **float**. |
| width | **float** | Width of a new [Section](../../section/) Zoom frame **float**. |
| height | **float** | Height of a new [Section](../../section/) Zoom frame **float**. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The section object referenced by the [Section](../../section/) Zoom frame [ISection](../../isection/). |

### Return Value

Created [Section](../../section/) Zoom object [ISectionZoomFrame](../../isectionzoomframe/).
## Remarks


This example demonstrates adding a [Section](../../section/) Zoom object to the end of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Adds a new [Section](../../section/) Zoom object to the end of a collection with a predefined image.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new [Section](../../section/) Zoom frame **float**. |
| y | **float** | Y coordinate of a new [Section](../../section/) Zoom frame **float**. |
| width | **float** | Width of a new [Section](../../section/) Zoom frame **float**. |
| height | **float** | Height of a new [Section](../../section/) Zoom frame **float**. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The section object referenced by the [Section](../../section/) Zoom frame [ISection](../../isection/). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image for the referenced slide [IPPImage](../../ippimage/) |

### Return Value

Created [Section](../../section/) Zoom object [ISectionZoomFrame](../../isectionzoomframe/).
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
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)