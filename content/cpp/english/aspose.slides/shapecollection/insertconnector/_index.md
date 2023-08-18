---
title: InsertConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index.
type: docs
weight: 430
url: /aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method


Creates a new [Connector](../../connector/), tunes it from default template and inserts it to the collection at the specified index.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
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

Created [Connector](../../connector/) object.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method


Creates a new [Connector](../../connector/) and inserts it to the collection at the specified index.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
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

Created [Connector](../../connector/) object.

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)