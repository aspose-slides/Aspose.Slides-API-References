---
title: add_connector method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Maakt een nieuw connectorvorm met standaard sjabloonopmaak en voegt het toe aan het einde van de vormverzameling.

### Retourwaarde

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de toe te voegen connectorvorm. |
| x | **float** | De x-coördinaat van het frame van de connector, in points. |
| y | **float** | De y-coördinaat van het frame van de connector, in points. |
| width | **float** | De breedte van het frame van de connector, in points. |
| height | **float** | De hoogte van het frame van de connector, in points. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Maakt een nieuw connectorvorm en voegt het toe aan het einde van de vormverzameling, optioneel met standaard sjabloonopmaak.

### Retourwaarde

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de te creëren connectorvorm. |
| x | **float** | De x-coördinaat van het frame van de connector, in points. |
| y | **float** | De y-coördinaat van het frame van de connector, in points. |
| width | **float** | De breedte van het frame van de connector, in points. |
| height | **float** | De hoogte van het frame van de connector, in points. |
| create_from_template | **bool** | True om standaard sjabloonopmaak toe te passen (non-empty name, simple style); <br/><br/>            false om de connector te maken met standaard eigenschapswaarden. |



### Zie ook
* klasse [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)