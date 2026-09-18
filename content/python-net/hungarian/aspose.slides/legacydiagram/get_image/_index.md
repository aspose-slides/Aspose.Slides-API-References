---
title: get_image method
second_title: Aspose.Slides a Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/legacydiagram/get_image/
weight: 50
---
## get_image(self) {#}
A shape thumbnail-t adja vissza.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Visszatérési érték

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
A shape thumbnail-t adja vissza.

### Visszatérési érték

Shape thumbnail vagy None abban az esetben, ha a ShapeThumbnailBounds.Appearance használatos, és a shape nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds típus. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`LegacyDiagram`](/slides/python-net/hu/aspose.slides/legacydiagram)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)