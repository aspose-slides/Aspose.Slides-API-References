---
title: get_image method
second_title: Aspose.Slides a Python számára .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Visszaadja a Shape bélyegképet.
            A ShapeThumbnailBounds.Shape alakzathétbélyeg határ típus alapértelmezés szerint van használva.

### Visszatérési érték

Shape bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a Shape bélyegképet.

### Visszatérési érték

Shape bélyegkép vagy None abban az esetben, amikor a ShapeThumbnailBounds.Appearance van használva és egy shape-nak nincsenek látható elemei.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds típus. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`Connector`](/slides/python-net/hu/aspose.slides/connector)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)