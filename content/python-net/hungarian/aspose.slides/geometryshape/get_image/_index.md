---
title: get_image method
second_title: Aspose.Slides a Python számára a .NET API referencián keresztül
description: 
type: docs
url: /hu/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
Visszaadja a shape thumbnail-et.  
ShapeThumbnailBounds.Shape shape thumbnail bounds típus van használva alapértelmezés szerint.

### Visszatér

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a shape thumbnail-et.

### Visszatér

Shape thumbnail vagy None, ha a ShapeThumbnailBounds.Appearance van használva, és a shape-nak nincsenek látható elemei.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds típus. |
| scale_x | **float** | X méretezés |
| scale_y | **float** | Y méretezés |

### Lásd még
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* felsorolás [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)