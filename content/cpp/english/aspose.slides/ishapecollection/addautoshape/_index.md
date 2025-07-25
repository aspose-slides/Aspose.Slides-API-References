---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new auto shape with default formatting and adds it to the end of the shape collection.
type: docs
weight: 313
url: /aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method


Creates a new auto shape with default formatting and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\\u2019s frame, in points. |
| width | **float** | The width of the shape\\u2019s frame, in points. |
| height | **float** | The height of the shape\\u2019s frame, in points. |

### Return Value

The newly created [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method


Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\\u2019s frame, in points. |
| width | **float** | The width of the shape\\u2019s frame, in points. |
| height | **float** | The height of the shape\\u2019s frame, in points. |
| createFromTemplate | **bool** | True to apply default template styling (simple style, centered text, and non-empty name) to the new shape; false to create the shape with all properties set to their default values. |

### Return Value

The newly created [IAutoShape](../../iautoshape/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)