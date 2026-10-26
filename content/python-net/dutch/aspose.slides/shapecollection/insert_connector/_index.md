---
title: insert_connector method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Maakt een nieuw connector-object aan en voegt het in de shape-collectie in op de opgegeven index,
            waarbij de standaard sjabloon-opmaak wordt toegepast.

### Retour

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).

```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de connector-shape moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de in te voegen connector-shape. |
| x | **float** | De x-coördinaat van het frame van de connector, in points. |
| y | **float** | De y-coördinaat van het frame van de connector, in points. |
| width | **float** | De breedte van het frame van de connector, in points. |
| height | **float** | De hoogte van het frame van de connector, in points. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Maakt een nieuw connector-object aan en voegt het in de shape-collectie in op de opgegeven index,
            waarbij optioneel de standaard sjabloon-opmaak wordt toegepast.

### Retour

Het nieuw aangemaakte [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector).

```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de connector-shape moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de in te voegen connector-shape. |
| x | **float** | De x-coördinaat van het frame van de connector, in points. |
| y | **float** | De y-coördinaat van het frame van de connector, in points. |
| width | **float** | De breedte van het frame van de connector, in points. |
| height | **float** | De hoogte van het frame van de connector, in points. |
| create_from_template | **bool** | True om de standaard sjabloon-opmaak toe te passen (niet-lege naam, eenvoudige stijl);<br/><br/>            false om de connector te maken met de standaard eigenschapswaarden. |



### Zie ook
* class [`IConnector`](/slides/python-net/nl/aspose.slides/iconnector)
* class [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)