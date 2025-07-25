---
title: InsertConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling.
type: docs
weight: 430
url: /aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method


Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
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

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method


Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
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
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)