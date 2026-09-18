---
title: add_group_shape method
second_title: Aspose.Slides a .NET API hivatkozáson keresztül a Pythonhoz
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Létrehoz egy új üres csoport alakzatot, és a forma gyűjtemény végéhez adja hozzá.
A csoport kerete automatikusan igazodik, hogy befogadja a hozzáadott alakzatokat.

### Visszatérési érték

Az újonnan létrehozott [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape).

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Létrehoz egy új csoport alakzatot, átalakítja a megadott SVG képet egyedi alakzatokká,
és az eredményül kapott csoportot a forma gyűjtemény végéhez adja hozzá.

### Visszatérési érték

Az újonnan létrehozott [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape).

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) | A [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage), amely vektor tartalmat tartalmaz a alakzatokká alakításhoz. |
| x | **float** | A csoport keretének x-koordinátája pontban. |
| y | **float** | A csoport keretének y-koordinátája pontban. |
| width | **float** | A csoport keretének szélessége pontban. |
| height | **float** | A csoport keretének magassága pontban. |

### Lásd még
* osztály [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape)
* osztály [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)