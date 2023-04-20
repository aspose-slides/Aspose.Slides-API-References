---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new PictureFrame and inserts it to the collection at the specified index.
type: docs
weight: 456
url: /cpp/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method


Creates a new [PictureFrame](../../pictureframe/) and inserts it to the collection at the specified index.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which value should be inserted. |
| shapeType | [ShapeType](../../shapetype/) | The shape contained in the set [ShapeType](../../shapetype/) of shapes, except all sorts of lines:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| width | **float** | The width of shape's frame. |
| height | **float** | The height of shape's frame. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The image of picture frame. |

### Return Value

Created [PictureFrame](../../pictureframe/) object.

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)