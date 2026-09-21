---
title: add_connector method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Maakt een nieuw connectorobject met de standaard sjabloonopmaak en voegt het toe aan het einde van de vormverzameling.

### Retourwaarde

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de connectorvorm die moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het kader van de connector, in punten. |
| y | **float** | De y-coördinaat van het kader van de connector, in punten. |
| width | **float** | De breedte van het kader van de connector, in punten. |
| height | **float** | De hoogte van het kader van de connector, in punten. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Maakt een nieuw connectorobject en voegt het toe aan het einde van de vormverzameling, met optionele toepassing van de standaard sjabloonopmaak.

### Retourwaarde

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de connectorvorm die moet worden aangemaakt. |
| x | **float** | De x-coördinaat van het kader van de connector, in punten. |
| y | **float** | De y-coördinaat van het kader van de connector, in punten. |
| width | **float** | De breedte van het kader van de connector, in punten. |
| height | **float** | De hoogte van het kader van de connector, in punten. |
| create_from_template | **bool** | True om de standaard sjabloonopmaak toe te passen (niet-lege naam, eenvoudige stijl); <br/><br/>false om de connector te maken met standaard eigenschapswaarden. |



### Zie ook
* klasse [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)