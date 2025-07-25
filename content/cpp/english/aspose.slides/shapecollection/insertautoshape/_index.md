---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting.
type: docs
weight: 378
url: /aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method


Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the new auto shape. |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the auto shape to insert. |
| x | **float** | The x-coordinate of the shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\\u2019s frame, in points. |
| width | **float** | The width of the shape\\u2019s frame, in points. |
| height | **float** | The height of the shape\\u2019s frame, in points. |

### Return Value

The newly created [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method


Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the auto shape. |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the auto shape to insert. |
| x | **float** | The x-coordinate of the shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\\u2019s frame, in points. |
| width | **float** | The width of the shape\\u2019s frame, in points. |
| height | **float** | The height of the shape\\u2019s frame, in points. |
| createFromTemplate | **bool** | True to apply default template styling (including a non-empty name, simple style, and centered text); false to create the shape with all properties set to their defaults. |

### Return Value

The newly created [IAutoShape](../../iautoshape/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)