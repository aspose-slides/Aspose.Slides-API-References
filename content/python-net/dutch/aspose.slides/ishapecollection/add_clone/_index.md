---
title: add_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.
            De gekloonde vorm behoudt de positie en grootte van het origineel.

### Retour

De nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.
            De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`.

### Retour

De nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm, in punten. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.

### Retour

De nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De vorm om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm, in punten. |
| width | **float** | De breedte van het frame van de gekloonde vorm, in punten. |
| height | **float** | De hoogte van het frame van de gekloonde vorm, in punten. |



### Zie ook
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)