---
title: get_image method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja az alakzat bélyegképét.
            ShapeThumbnailBounds.Shape alakzat bélyegkép határ típusa van alapértelmezés szerint használva.

### Visszatérési érték

Alakzat bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja az alakzat bélyegképét.

### Visszatérési érték

Alakzat bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance van használva, és az alakzatnak nincsenek látható elemei.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Alakzat bélyegkép határ típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`InkActions`](/slides/python-net/hu/aspose.slides.ink/inkactions)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)