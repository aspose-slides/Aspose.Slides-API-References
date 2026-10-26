---
title: add_auto_shape method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Új automatikus alakzatot hoz létre alapértelmezett formázással, és a alakzatgyűjtemény végéhez adja hozzá.

### Visszatérési érték

Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A hozzáadandó automatikus alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| x | **float** | Az alakzat keretének x koordinátája pontban. |
| y | **float** | Az alakzat keretének y koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Új automatikus alakzatot hoz létre, és a alakzatgyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva.

### Visszatérési érték

Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A hozzáadandó automatikus alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| x | **float** | Az alakzat keretének x koordinátája pontban. |
| y | **float** | Az alakzat keretének y koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| create_from_template | **bool** | True, ha az új alakzatra alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg és nem üres név) alkalmaz; false, ha az alakzatot minden tulajdonság alapértelmezett értékével hozza létre. |



### Lásd még
* osztály [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)