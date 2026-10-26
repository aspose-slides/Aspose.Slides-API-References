---
title: add_group_shape method
second_title: Aspose.Slides a Python számára .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Létrehoz egy új üres csoport alakzatot, és a alakzatgyűjtemény végére adja hozzá.
            A csoport kerete automatikusan igazodik, hogy illeszkedjen a hozzáadott alakzatokhoz.

### Returns

Az újonnan létrehozott [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Létrehoz egy új csoport alakzatot, a megadott SVG képet egyedi alakzatokká alakítja, és az eredményül kapott csoportot a alakzatgyűjtemény végére adja hozzá.

### Returns

Az újonnan létrehozott [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) | A [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) vektoros tartalmat tartalmaz, amely alakzatokká konvertálható. |
| x | **float** | A csoport keretének x-koordinátája pontban. |
| y | **float** | A csoport keretének y-koordinátája pontban. |
| width | **float** | A csoport keretének szélessége pontban. |
| height | **float** | A csoport keretének magassága pontban. |



### See Also
* osztály [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* osztály [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)