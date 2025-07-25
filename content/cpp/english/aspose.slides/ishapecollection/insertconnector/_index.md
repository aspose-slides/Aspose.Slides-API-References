---
title: InsertConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling.
type: docs
weight: 391
url: /aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method


Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the connector shape. |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the connector\\u2019s frame, in points. |
| width | **float** | The width of the connector\\u2019s frame, in points. |
| height | **float** | The height of the connector\\u2019s frame, in points. |

### Return Value

The newly created [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method


Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the connector shape. |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the connector\\u2019s frame, in points. |
| width | **float** | The width of the connector\\u2019s frame, in points. |
| height | **float** | The height of the connector\\u2019s frame, in points. |
| createFromTemplate | **bool** | True to apply default template styling (non-empty name, simple style); false to create the connector with default property values. |

### Return Value

The newly created [IConnector](../../iconnector/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)