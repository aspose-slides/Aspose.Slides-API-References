---
title: add_clone method
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez.
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
Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez.
Az új alakzat megtartja a `source_shape` szélességét és magasságát.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) a klónozáshoz. |
| x | **float** | A klónozott alakzat keretének x-koordinátája pontokban. |
| y | **float** | A klónozott alakzat keretének y-koordinátája pontokban. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`IShape`](/slides/python-net/hu/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A shape a klónozáshoz. |
| x | **float** | A klónozott alakzat keretének x-koordinátája pontokban. |
| y | **float** | A klónozott alakzat keretének y-koordinátája pontokban. |
| width | **float** | A klónozott alakzat keretének szélessége pontokban. |
| height | **float** | A klónozott alakzat keretének magassága pontokban. |

### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)