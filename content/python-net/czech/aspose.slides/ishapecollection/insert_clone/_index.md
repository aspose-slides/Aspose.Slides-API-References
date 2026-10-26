---
title: insert_clone method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.
            Klonovaný tvar zachovává polohu a velikost originálu.

### Vrací

Nově vytvořený [`IShape`](/slides/python-net/cs/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se vloží klonovaný tvar. |
| source_shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) k naklonování. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.
            Nový tvar zachovává šířku a výšku `source_shape`.

### Vrací

Nově vytvořený [`IShape`](/slides/python-net/cs/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se vloží klonovaný tvar. |
| source_shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) k naklonování. |
| x | **float** | x-souřadnice rámečku klonovaného tvaru, v bodech. |
| y | **float** | y-souřadnice rámečku klonovaného tvaru, v bodech. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.

### Vrací

Nově vytvořený [`IShape`](/slides/python-net/cs/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se vloží klonovaný tvar. |
| source_shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) k naklonování. |
| x | **float** | x-souřadnice rámečku klonovaného tvaru, v bodech. |
| y | **float** | y-souřadnice rámečku klonovaného tvaru, v bodech. |
| width | **float** | Šířka rámečku klonovaného tvaru, v bodech. |
| height | **float** | Výška rámečku klonovaného tvaru, v bodech. |



### Viz také
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)