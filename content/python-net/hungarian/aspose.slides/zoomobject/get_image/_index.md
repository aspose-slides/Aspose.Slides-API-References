---
title: get_image method
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja az alakzat bélyegképét.
            Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép határérték típusa van használva.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Az alakzat bélyegkép határérték típusa. |
| scale_x | **float** | X méretezés |
| scale_y | **float** | Y méretezés |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* osztály [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)