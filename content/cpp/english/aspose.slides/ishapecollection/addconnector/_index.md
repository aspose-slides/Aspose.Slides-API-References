---
title: AddConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new connector shape with default template styling and adds it to the end of the shape collection.
type: docs
weight: 378
url: /aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) method


Creates a new connector shape with default template styling and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the connector shape to add. |
| x | **float** | The x-coordinate of the connector\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the connector\\u2019s frame, in points. |
| width | **float** | The width of the connector\\u2019s frame, in points. |
| height | **float** | The height of the connector\\u2019s frame, in points. |

### Return Value

The newly created [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of the connector shape to create. |
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