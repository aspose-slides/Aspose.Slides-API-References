---
title: add_group_shape method
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów.
            Ramka grupy zostanie automatycznie dopasowana, aby pomieścić wszystkie dodane do niej kształty.

### Zwraca

Nowo utworzony [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Tworzy nowy kształt grupy, konwertuje określony obraz SVG na pojedyncze kształty i dodaje powstałą grupę na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage) zawierający zawartość wektorową do konwersji na kształty. |
| x | **float** | Współrzędna x ramki grupy, w punktach. |
| y | **float** | Współrzędna y ramki grupy, w punktach. |
| width | **float** | Szerokość ramki grupy, w punktach. |
| height | **float** | Wysokość ramki grupy, w punktach. |



### Zobacz także
* klasa [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape)
* klasa [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)