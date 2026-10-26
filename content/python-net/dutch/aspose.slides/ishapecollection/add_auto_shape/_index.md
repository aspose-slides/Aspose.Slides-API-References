---
title: add_auto_shape method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de
            vormverzameling.

### Retour

De nieuw aangemaakte [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | Het [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de auto-vorm die moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het vormkader, in punten. |
| y | **float** | De y-coördinaat van het vormkader, in punten. |
| width | **float** | De breedte van het vormkader, in punten. |
| height | **float** | De hoogte van het vormkader, in punten. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Maakt een nieuwe auto-vorm en voegt deze toe aan het einde van de vormverzameling, eventueel
            met standaard-sjabloonopmaak geïnitialiseerd.

### Retour

De nieuw aangemaakte [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | Het [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) van de auto-vorm die moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het vormkader, in punten. |
| y | **float** | De y-coördinaat van het vormkader, in punten. |
| width | **float** | De breedte van het vormkader, in punten. |
| height | **float** | De hoogte van het vormkader, in punten. |
| create_from_template | **bool** | True om de standaard-sjabloonstijl toe te passen (eenvoudige stijl, gecentreerde tekst en een niet-lege naam)<br/><br/>            op de nieuwe vorm; false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |



### Zie ook
* klasse [`IAutoShape`](/slides/python-net/nl/aspose.slides/iautoshape)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)