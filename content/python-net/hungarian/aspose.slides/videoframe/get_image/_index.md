---
title: get_image method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Visszaadja az alakzat bélyegképét.
Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép határ típusa van használva.

### Visszatérési érték
Shape bélyegkép.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja az alakzat bélyegképét.

### Visszatérési érték
Shape bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance van használva, és egy alakzatnak nincsenek látható elemei.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape bélyegkép határ típusa. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |

### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* osztály [`VideoFrame`](/slides/python-net/hu/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)