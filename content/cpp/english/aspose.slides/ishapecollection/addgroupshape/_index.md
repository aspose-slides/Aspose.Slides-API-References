---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new empty group shape and adds it to the end of the shape collection. The group\\u2019s frame will automatically adjust to fit any shapes added to it.
type: docs
weight: 352
url: /aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() method


Creates a new empty group shape and adds it to the end of the shape collection. The group\\u2019s frame will automatically adjust to fit any shapes added to it.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Return Value

The newly created [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method


Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | The [ISvgImage](../../isvgimage/) containing vector content to convert into shapes. |
| x | **float** | The x-coordinate of the group\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the group\\u2019s frame, in points. |
| width | **float** | The width of the group\\u2019s frame, in points. |
| height | **float** | The height of the group\\u2019s frame, in points. |

### Return Value

The newly created [IGroupShape](../../igroupshape/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [IShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)