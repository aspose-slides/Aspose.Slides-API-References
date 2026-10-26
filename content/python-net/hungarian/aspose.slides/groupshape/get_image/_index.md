---
title: get_image method
second_title: Aspose.Slides a Python számára .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a forma bélyegképét.  
Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa van használatban.

### Visszatérési érték

Forma bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a forma bélyegképét.

### Visszatérési érték

Forma bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance van használatban és a forma nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | A forma bélyegkép határoló típusa. |
| scale_x | **float** | X méretarány |
| scale_y | **float** | Y méretarány |



### Lásd még
* osztály [`GroupShape`](/slides/python-net/hu/aspose.slides/groupshape)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)