---
title: get_image method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a forma bélyegképét.
            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határtípus van használva.

### Visszatérési érték

Alakzat bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a forma bélyegképét.

### Visszatérési érték

Alakzat bélyegkép, vagy None, ha a ShapeThumbnailBounds.Appearance van használva, és a forma nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Alakzat bélyegkép határtípus. |
| scale_x | **float** | X méretezés |
| scale_y | **float** | Y méretezés |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`Ink`](/slides/python-net/hu/aspose.slides.ink/ink)
* felsorolás [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)