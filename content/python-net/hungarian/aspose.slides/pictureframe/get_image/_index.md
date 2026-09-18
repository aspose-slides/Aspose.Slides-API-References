---
title: get_image method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
A forma bélyegképét adja vissza.  
Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határ típusa kerül felhasználásra.

### Visszatér

Alak bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
A forma bélyegképét adja vissza.

### Visszatér

Alak bélyegkép vagy **None**, ha a ShapeThumbnailBounds.Appearance van használva, és a shape nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape bélyegkép határ típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)