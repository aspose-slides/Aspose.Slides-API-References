---
title: get_image method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
A forma bélyegképét adja vissza.
            ShapeThumbnailBounds.Shape shape thumbnail bounds típus van használva alapértelmezetten.

### Visszatér

Forma bélyegkép.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
A forma bélyegképét adja vissza.

### Visszatér

Forma bélyegkép vagy None abban az esetben, ha a ShapeThumbnailBounds.Appearance van használva, és a forma nem rendelkezik látható elemekkel.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds típus. |
| scale_x | **float** | X méretarány |
| scale_y | **float** | Y méretarány |

### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* osztály [`ZoomFrame`](/slides/python-net/hu/aspose.slides/zoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)