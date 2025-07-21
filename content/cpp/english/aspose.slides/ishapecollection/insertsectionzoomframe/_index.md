---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index.
type: docs
weight: 131
url: /aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method


Creates a new [Section](../../section/) Zoom frame and inserts it into to the shape collection at the specified index.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the [Section](../../section/) Zoom frame. |
| x | **float** | The x-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| y | **float** | The y-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| width | **float** | The width of the new [Section](../../section/) Zoom frame, in points. |
| height | **float** | The height of the new [Section](../../section/) Zoom frame, in points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The [ISection](../../isection/) referenced by the [Section](../../section/) Zoom frame; must belong to this presentation and contain at least one slide. |

### Return Value

The newly created [ISectionZoomFrame](../../isectionzoomframe/).
## Remarks


This example demonstrates the creation and inserting a [Section](../../section/) Zoom object at the specified index of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Creates a new [Section](../../section/) Zoom frame with a predefined image and inserts it into to the shape collection at the specified index.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the [Section](../../section/) Zoom frame. |
| x | **float** | The x-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| y | **float** | The y-coordinate of the new [Section](../../section/) Zoom frame, in points. |
| width | **float** | The width of the new [Section](../../section/) Zoom frame, in points. |
| height | **float** | The height of the new [Section](../../section/) Zoom frame, in points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The [ISection](../../isection/) referenced by the [Section](../../section/) Zoom frame; must belong to this presentation and contain at least one slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image to display within the [Section](../../section/) Zoom frame. |

### Return Value

The newly created [ISectionZoomFrame](../../isectionzoomframe/).
## Remarks


This example demonstrates the creation and inserting a [Section](../../section/) Zoom object at the specified index of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)