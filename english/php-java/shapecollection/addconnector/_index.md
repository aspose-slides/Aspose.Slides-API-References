---
title: addConnector
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 120
url: /php-java/shapecollection/addconnector/
---

## addConnector(int shapeType, float x, float y, float width, float height)  method

 Creates a new Connector, tunes it from default template and adds it to the end of the collection.
 

 The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
 
```php
  // Instantiates a presentation class that represents a PPTX file
  $pres = new Presentation();
  try {
    // Accesses the shapes collection for a specific slide
    $shapes = $pres->getSlides()->get_Item(0)->getShapes();
    // Adds an Ellipse autoshape
    $ellipse = $shapes->addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
    // Adds a Rectangle autoshape
    $rectangle = $shapes->addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
    // Adds a connector shape to the slide shape collection
    $connector = $shapes->addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
    // Connects the shapes using the connector
    $connector->setStartShapeConnectedTo($ellipse);
    $connector->setEndShapeConnectedTo($rectangle);
    // Calls reroute that sets the automatic shortest path between shapes
    $connector->reroute();
    // Saves the presentation
    $pres->save("Shapes-connector.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

### Returns
[Connector](../../connector)


---


## addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)  method

 Creates a new Connector and adds it to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Returns
[Connector](../../connector)


---


