---
title: insert_clone method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index.
            De gekloonde vorm behoudt de positie en grootte van het origineel.

### Retourwaarde

De nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index.
            De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`.

### Retourwaarde

De nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm, in punten. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index.

### Retourwaarde

De nieuw aangemaakte [`IShape`](/slides/python-net/nl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| source_shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | De [`IShape`](/slides/python-net/nl/aspose.slides/ishape) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm, in punten. |
| width | **float** | De breedte van het frame van de gekloonde vorm, in punten. |
| height | **float** | De hoogte van het frame van de gekloonde vorm, in punten. |



### Zie ook
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)