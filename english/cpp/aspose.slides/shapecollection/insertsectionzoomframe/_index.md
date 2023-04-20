---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Section Zoom object and inserts into to a collection at the specified index.
type: docs
weight: 144
url: /cpp/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method


Creates a new [Section](../../section/) Zoom object and inserts into to a collection at the specified index.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which [Section](../../section/) Zoom frame should be inserted. |
| x | **float** | X coordinate of a new [Section](../../section/) Zoom frame **float**. |
| y | **float** | Y coordinate of a new [Section](../../section/) Zoom frame **float**. |
| width | **float** | Width of a new [Section](../../section/) Zoom frame **float**. |
| height | **float** | Height of a new [Section](../../section/) Zoom frame **float**. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The slide object referenced by the [Section](../../section/) Zoom frame [ISection](../../isection/). |

### Return Value

Created [Section](../../section/) Zoom object [ISectionZoomFrame](../../isectionzoomframe/).
## Remarks


This example demonstrates the creation and inserting a [Section](../../section/) Zoom object at the specified index of a collection (assume that there are at least two sections in the \"Presentation.pptx\" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Creates a new [Section](../../section/) Zoom object and inserts it to a collection at the specified index.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which [Section](../../section/) Zoom frame should be inserted. |
| x | **float** | X coordinate of a new [Section](../../section/) Zoom frame **float**. |
| y | **float** | Y coordinate of a new [Section](../../section/) Zoom frame **float**. |
| width | **float** | Width of a new [Section](../../section/) Zoom frame **float**. |
| height | **float** | Height of a new [Section](../../section/) Zoom frame **float**. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | The slide object referenced by the [Section](../../section/) Zoom frame [ISection](../../isection/). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image for the referenced slide [IPPImage](../../ippimage/) |

### Return Value

Created [Section](../../section/) Zoom object [ISectionZoomFrame](../../isectionzoomframe/).
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
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)