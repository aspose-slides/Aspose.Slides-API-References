---
title: get_image method
second_title: Aspose.Slides Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Alakzat bélyegképet ad vissza.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Visszatérési érték

Alakzat bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Alakzat bélyegképet ad vissza.

### Visszatérési érték

Alakzat bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance van használva, és az alakzatnak nincsenek látható elemei.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Alakzat bélyegkép határ típus. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`AudioFrame`](/slides/python-net/hu/aspose.slides/audioframe)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)