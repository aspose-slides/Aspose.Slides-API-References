---
title: AddConnector()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new connector shape with default template styling and adds it to the end of the shape collection.
type: docs
weight: 417
url: /aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) method


Creates a new connector shape with default template styling and adds it to the end of the shape collection.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
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

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
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
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)