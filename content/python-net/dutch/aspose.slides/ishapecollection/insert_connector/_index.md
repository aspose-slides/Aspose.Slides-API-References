---
title: insert_connector method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Maakt een nieuw connectorobject aan en voegt het toe aan de vormverzameling op de opgegeven index, waarbij de standaard sjabloonopmaak wordt toegepast.

### Retourwaarde

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de connectorvorm moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de connectorvorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Maakt een nieuw connectorobject aan en voegt het toe aan de vormverzameling op de opgegeven index, met de mogelijkheid om standaard sjabloonopmaak toe te passen.

### Retourwaarde

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de connectorvorm moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de connectorvorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |
| create_from_template | **bool** | True om standaard sjabloonopmaak toe te passen (niet-lege naam, eenvoudige stijl);<br/><br/>false om de connector te creëren met standaard eigenschapswaarden. |



### Zie ook
* klasse [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)