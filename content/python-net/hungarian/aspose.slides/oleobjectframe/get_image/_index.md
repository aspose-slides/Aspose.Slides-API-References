---
title: get_image method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/oleobjectframe/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a forma bélyegképét.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Visszatérési érték

Forma bélyegkép.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a forma bélyegképét.

### Visszatérési érték

Shape thumbnail vagy None, ha a ShapeThumbnailBounds.Appearance van használva, és a forma nem tartalmaz látható elemeket.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail határérték típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`OleObjectFrame`](/slides/python-net/hu/aspose.slides/oleobjectframe)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)