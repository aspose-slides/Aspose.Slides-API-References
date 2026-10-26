---
title: get_image method
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
Visszaadja a forma bélyegképét.
            ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa alapértelmezés szerint használatos.

### Visszatérési érték

Forma bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a forma bélyegképét.

### Visszatérési érték

Forma bélyegkép vagy None abban az esetben, ha a ShapeThumbnailBounds.Appearance van használva, és egy alaknak nincsenek látható elemei.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Forma bélyegkép határoló típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`Chart`](/slides/python-net/hu/aspose.slides.charts/chart)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)