---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_connector/
weight: 260
---


## insert_connector {#int-shapetype-float-float-float-float}
Creates a new connector shape and inserts it into the shape collection at the specified index,
            applying default template styling.

### Returns

The newly created [`IConnector`](/slides/python-net/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the connector shape. |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |


## insert_connector {#int-shapetype-float-float-float-float-bool}
Creates a new connector shape and inserts it into the shape collection at the specified index,
            optionally applying default template styling.

### Returns

The newly created [`IConnector`](/slides/python-net/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the connector shape. |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |
| create_from_template | **bool** | True to apply default template styling (non-empty name, simple style);<br/><br/>            false to create the connector with default property values. |



### See Also
* class [`IConnector`](/slides/python-net/aspose.slides/iconnector)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

