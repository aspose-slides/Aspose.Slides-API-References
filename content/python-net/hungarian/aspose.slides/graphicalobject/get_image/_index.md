---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja az alakzat bélyegképét.
            ShapeThumbnailBounds.Shape alakzat bélyegkép határ típusa kerül alapértelmezés szerint felhasználásra.

### Visszatérési érték

Alakzat bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja az alakzat bélyegképét.

### Visszatérési érték

Alakzat bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance kerül használatra, és az alakzatnak nincsenek látható elemei.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Az alakzat bélyegkép határ típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)