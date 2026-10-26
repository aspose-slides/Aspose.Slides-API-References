---
title: get_image method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Visszaadja az alakzat bélyegképét.
            ShapeThumbnailBounds.Shape alakzat bélyegkép határoló típusa van használva alapértelmezés szerint.

### Visszatérési érték

Alakzat bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja az alakzat bélyegképét.

### Visszatérési érték

Alakzat bélyegkép vagy None abban az esetben, amikor a ShapeThumbnailBounds.Appearance van használva, és egy alakzat nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Alakzat bélyegkép határoló típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)