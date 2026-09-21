---
title: insert_auto_shape method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Maakt een nieuwe auto shape en voegt deze toe aan de shape-collectie op de opgegeven index, en past de standaard sjabloonopmaak toe.

### Retourneert

De nieuw gemaakte [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de nieuwe auto shape moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de auto shape die ingevoegd moet worden. |
| x | **float** | De x-coördinaat van het frame van de shape, in punten. |
| y | **float** | De y-coördinaat van het frame van de shape, in punten. |
| width | **float** | De breedte van het frame van de shape, in punten. |
| height | **float** | De hoogte van het frame van de shape, in punten. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Maakt een nieuwe auto shape en voegt deze toe aan de shape-collectie op de opgegeven index, optioneel initialiserend met de standaard sjabloonopmaak.

### Retourneert

De nieuw gemaakte [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de auto shape moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de auto shape die ingevoegd moet worden. |
| x | **float** | De x-coördinaat van het frame van de shape, in punten. |
| y | **float** | De y-coördinaat van het frame van de shape, in punten. |
| width | **float** | De breedte van het frame van de shape, in punten. |
| height | **float** | De hoogte van het frame van de shape, in punten. |
| create_from_template | **bool** | True om de standaard sjabloonopmaak toe te passen (inclusief een niet-lege naam, eenvoudige stijl en gecentreerde tekst); <br/><br/> false om de shape te maken met alle eigenschappen ingesteld op hun standaardwaarden. |



### Zie ook
* klasse [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)