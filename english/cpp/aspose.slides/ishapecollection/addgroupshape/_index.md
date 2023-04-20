---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.
type: docs
weight: 352
url: /cpp/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() method


Creates a new [GroupShape](../../groupshape/) and adds it to the end of the collection. [GroupShape](../../groupshape/) frame size and position will be fitted to content when new shape will be added into the [GroupShape](../../groupshape/).

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Return Value

Created [GroupShape](../../groupshape/) object.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method


Creates a new [GroupShape](../../groupshape/), fills it with converted shapes from SVG and adds it to the end of the collection.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg image object [ISvgImage](../../isvgimage/) |
| x | **float** | The X coordinate for the left side of the shape group frame. |
| y | **float** | The Y coordinate for the top side of the shape group frame. |
| width | **float** | The width of the group of the shape group frame. |
| height | **float** | The height of a group of the shape group frame. |

### Return Value

Created [GroupShape](../../groupshape/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [IShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)