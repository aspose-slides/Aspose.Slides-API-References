---
title: get_image method
second_title: Aspose.Slides Pythonhoz a .NET API Referencián keresztül
description: 
type: docs
url: /hu/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
Visszaadja a shape bélyegképet.  
ShapeThumbnailBounds.Shape shape bélyegkép határ típus alapértelmezés szerint használatos.

### Visszatér

Shape bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a shape bélyegképet.

### Visszatér

Shape bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance van használatban, és egy shape nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail határ típus. |
| scale_x | **float** | X méretezés |
| scale_y | **float** | Y méretezés |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* osztály [`SmartArtShape`](/slides/python-net/hu/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)