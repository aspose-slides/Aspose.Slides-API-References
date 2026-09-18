---
title: get_image method
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/summaryzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a forma bélyegképét.
            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határ típusa használatos.

### Visszatérési érték

Forma bélyegkép.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a forma bélyegképét.

### Visszatérési érték

Forma bélyegkép vagy None, ha a ShapeThumbnailBounds.Appearance van használatban, és a forma nem rendelkezik látható elemekkel.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Forma bélyegkép határ típus. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |

### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* osztály [`SummaryZoomFrame`](/slides/python-net/hu/aspose.slides/summaryzoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)