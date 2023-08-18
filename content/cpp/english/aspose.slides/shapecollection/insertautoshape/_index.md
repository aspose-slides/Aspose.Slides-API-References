---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API Reference
description: "Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter."
type: docs
weight: 378
url: /aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method


Creates a new [AutoShape](../../autoshape/), tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which value should be inserted. |
| shapeType | [ShapeType](../../shapetype/) | An [ShapeType](../../shapetype/) of shape. |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| width | **float** | The width of shape's frame. |
| height | **float** | The height of shape's frame. |

### Return Value

Created [AutoShape](../../autoshape/) object.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method


Creates a new [AutoShape](../../autoshape/) and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which value should be inserted. |
| shapeType | [ShapeType](../../shapetype/) | An [ShapeType](../../shapetype/) of shape. |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| width | **float** | The width of shape's frame. |
| height | **float** | The height of shape's frame. |
| createFromTemplate | **bool** | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Return Value

Created [AutoShape](../../autoshape/) object.

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)