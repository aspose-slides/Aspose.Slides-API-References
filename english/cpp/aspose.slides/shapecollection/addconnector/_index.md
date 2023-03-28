---
title: AddConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Connector, tunes it from default template and adds it to the end of the collection.
type: docs
weight: 417
url: /cpp/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector([ShapeType](../../shapetype/), **float**, **float**, **float**, **float**) method


Creates a new [Connector](../../connector/), tunes it from default template and adds it to the end of the collection.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
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
## Remarks



The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantiates a presentation class that represents a PPTX file
auto input = System::MakeObject<Presentation>();

// Accesses the shapes collection for a specific slide
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Adds an Ellipse autoshape
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Adds a Rectangle autoshape
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Adds a connector shape to the slide shape collection
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Connects the shapes using the connector
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Calls reroute that sets the automatic shortest path between shapes
connector->Reroute();

// Saves the presentation
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Enum [ShapeType](../../shapetype/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## ShapeCollection::AddConnector([ShapeType](../../shapetype/), **float**, **float**, **float**, **float**, **bool**) method


Creates a new [Connector](../../connector/) and adds it to the end of the collection.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Enum [ShapeType](../../shapetype/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
