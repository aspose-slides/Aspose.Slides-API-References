---
title: insert_connector method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, och tillämpar standardmallens stil.

### Returnerar

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the connector shape. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, med möjlighet att tillämpa standardmallens stil.

### Returnerar

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the connector shape. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) of the connector shape to insert. |
| x | **float** | The x-coordinate of the connector’s frame, in points. |
| y | **float** | The y-coordinate of the connector’s frame, in points. |
| width | **float** | The width of the connector’s frame, in points. |
| height | **float** | The height of the connector’s frame, in points. |
| create_from_template | **bool** | True för att tillämpa standardmallens stil (icke-tomt namn, enkel stil);<br/><br/>            false för att skapa anslutningen med standardvärden för egenskaperna. |



### Se också
* klass [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)