---
title: insert_auto_shape method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Creëert een nieuwe auto-vorm en voegt deze toe aan de vormcollectie op de opgegeven index, met toepassing van de standaard sjabloonopmaak.

### Retour

De nieuw aangemaakte [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de nieuwe auto-vorm moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de auto-vorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de vorm, in points. |
| y | **float** | De y-coördinaat van het frame van de vorm, in points. |
| width | **float** | De breedte van het frame van de vorm, in points. |
| height | **float** | De hoogte van het frame van de vorm, in points. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Creëert een nieuwe auto-vorm en voegt deze toe aan de vormcollectie op de opgegeven index, met de optie om deze te initialiseren met de standaard sjabloonstijl.

### Retour

De nieuw aangemaakte [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de auto-vorm moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | De [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de auto-vorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de vorm, in points. |
| y | **float** | De y-coördinaat van het frame van de vorm, in points. |
| width | **float** | De breedte van het frame van de vorm, in points. |
| height | **float** | De hoogte van het frame van de vorm, in points. |
| create_from_template | **bool** | True om de standaard sjabloonstijl toe te passen (inclusief een niet-lege naam, eenvoudige stijl en gecentreerde tekst); <br/><br/> false om de vorm te creëren met alle eigenschappen ingesteld op hun standaardwaarden. |



### Zie ook
* klasse [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)