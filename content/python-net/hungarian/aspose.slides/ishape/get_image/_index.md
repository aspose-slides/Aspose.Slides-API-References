---
title: get_image method
second_title: Aspose.Slides Pythonhoz a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/ishape/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a shape bélyegképét.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Visszatér

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a shape bélyegképét.

### Visszatér

Shape thumbnail or None in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X scale |
| scale_y | **float** | Y scale |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)