---
title: insert_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Maakt een kopie van de opgegeven vorm en voegt deze in de vormcollectie in op de opgegeven index.
De gekloonde vorm behoudt de positie en grootte van het origineel.

### Retour

Het nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Maakt een kopie van de opgegeven vorm en voegt deze in de vormcollectie in op de opgegeven index.
De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`.

### Retour

Het nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm, in punten. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Maakt een kopie van de opgegeven vorm en voegt deze in de vormcollectie in op de opgegeven index.

### Retour

Het nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm, in punten. |
| width | **float** | De breedte van het frame van de gekloonde vorm, in punten. |
| height | **float** | De hoogte van het frame van de gekloonde vorm, in punten. |



### Zie ook
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)