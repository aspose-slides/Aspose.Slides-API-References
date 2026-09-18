---
title: add_auto_shape method
second_title: Aspose.Slides Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Létrehoz egy új automatikus alakzatot alapértelmezett formázással, és a alakzat-gyűjtemény végéhez adja.

### Visszatér
Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | Az [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) az auto shape-hoz. |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Létrehoz egy új automatikus alakzatot, és a alakzat-gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonformázással inicializálva.

### Visszatér
Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | Az [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) az auto shape-hoz. |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| create_from_template | **bool** | True, ha az alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg és nem üres név)<br/><br/>            a új alakzatra alkalmazza; false, ha az alakzatot minden tulajdonságot az alapértelmezett értékekre állítva hozza létre. |



### Lásd még
* osztály [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)