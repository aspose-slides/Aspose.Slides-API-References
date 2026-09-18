---
title: get_image method
second_title: Aspose.Slides for Python .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja az alakzat bélyegképét.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type az alapértelmezett módon kerül használatra.

### Visszatérési érték

Alakzat bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja az alakzat bélyegképét.

### Visszatérési érték

Alakzat bélyegkép vagy None abban az esetben, ha a ShapeThumbnailBounds.Appearance kerül felhasználásra, és egy alakzaton nincs látható elem.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X méretezés |
| scale_y | **float** | Y méretezés |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* osztály [`SmartArt`](/slides/python-net/hu/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)