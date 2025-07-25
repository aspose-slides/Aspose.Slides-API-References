---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new picture frame containing the specified image and adds it to the end of the shape collection.
type: docs
weight: 404
url: /aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method


Creates a new picture frame containing the specified image and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Specifies the shape type contained in [ShapeType](../../shapetype/), except for all kinds of lines:

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
| x | **float** | The x-coordinate of the picture frame, in points. |
| y | **float** | The y-coordinate of the picture frame, in points. |
| width | **float** | The width of the picture frame, in points. |
| height | **float** | The height of the picture frame, in points. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | The [IPPImage](../../ippimage/) to display in the picture frame. |

### Return Value

The newly created [IPictureFrame](../../ipictureframe/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)