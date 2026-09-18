---
title: insert_clone method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Létrehoz egy másolatot a megadott alakzatról, és beilleszti azt az alakzatgyűjteménybe a megadott indexen.
            A klónozott alakzat megtartja az eredeti pozícióját és méretét.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló index, ahol a klónozott alakzatot be kell illeszteni. |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) a klónozáshoz. |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Létrehoz egy másolatot a megadott alakzatról, és beilleszti azt az alakzatgyűjteménybe a megadott indexen.
            Az új alakzat megtartja a `source_shape` szélességét és magasságát.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló index, ahol a klónozott alakzatot be kell illeszteni. |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) a klónozáshoz. |
| x | **float** | A klónozott alakzat keretének x koordinátája pontban. |
| y | **float** | A klónozott alakzat keretének y koordinátája pontban. |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Létrehoz egy másolatot a megadott alakzatról, és beilleszti azt az alakzatgyűjteménybe a megadott indexen.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló index, ahol a klónozott alakzatot be kell illeszteni. |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) a klónozáshoz. |
| x | **float** | A klónozott alakzat keretének x koordinátája pontban. |
| y | **float** | A klónozott alakzat keretének y koordinátája pontban. |
| width | **float** | A klónozott alakzat keretének szélessége pontban. |
| height | **float** | A klónozott alakzat keretének magassága pontban. |

### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)