---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_connector/
weight: 70
---


## add_connector {#shapetype-float-float-float-float}
Creates a new connector shape with default template styling and adds it to the end of the
            shape collection.

### Returns

The newly created [`IConnector`](/slides/python-net/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the connector shape to add. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |


## add_connector {#shapetype-float-float-float-float-bool}
Creates a new connector shape and adds it to the end of the shape collection,
            optionally applying default template styling.

### Returns

The newly created [`IConnector`](/slides/python-net/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the connector shape to create. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |
| create_from_template | **bool** | True to apply default template styling (non-empty name, simple style); <br/><br/>            false to create the connector with default property values. |



### See Also
* class [`IConnector`](/slides/python-net/aspose.slides/iconnector)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

