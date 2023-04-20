---
title: AddConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Connector, tunes it from default template and adds it to the end of the collection.
type: docs
weight: 378
url: /cpp/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) method


Creates a new [Connector](../../connector/), tunes it from default template and adds it to the end of the collection.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of shape. |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| width | **float** | The width of shape's frame. |
| height | **float** | The height of shape's frame. |

### Return Value

The zero-based index of the created shape.

Created [Connector](../../connector/) object.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


Creates a new [Connector](../../connector/) and adds it to the end of the collection.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | The [ShapeType](../../shapetype/) of shape. |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| width | **float** | The width of shape's frame. |
| height | **float** | The height of shape's frame. |
| createFromTemplate | **bool** | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Return Value

The zero-based index of the created shape.

Created [Connector](../../connector/) object.

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)