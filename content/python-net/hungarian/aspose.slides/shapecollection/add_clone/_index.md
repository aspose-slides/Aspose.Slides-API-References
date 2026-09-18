---
title: add_clone method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez.  
A klónozott alakzat megtartja az eredeti pozícióját és méretét.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

```python
def add_clone(self, source_shape):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) a klónozáshoz. |

## add_clone(self, source_shape, x, y) {#ishape-float-float}
Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez.  
Az új alakzat megtartja a `source_shape` szélességét és magasságát.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

```python
def add_clone(self, source_shape, x, y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A klónozandó alakzat. |
| x | **float** | Az új alakzat keretének x-koordinátája, pontban. |
| y | **float** | Az új alakzat keretének y-koordinátája, pontban. |

## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A klónozandó alakzat. |
| x | **float** | Az új alakzat keretének x-koordinátája, pontban. |
| y | **float** | Az új alakzat keretének y-koordinátája, pontban. |
| width | **float** | Az új alakzat keretének szélessége, pontban. |
| height | **float** | Az új alakzat keretének magassága, pontban. |

### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)