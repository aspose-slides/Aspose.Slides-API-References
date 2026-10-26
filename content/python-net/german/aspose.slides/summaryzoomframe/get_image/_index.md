---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/summaryzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Gibt Shape-Miniatur zurück.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Rückgabe

Shape-Miniatur.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt Shape-Miniatur zurück.

### Rückgabe

Shape-Miniatur oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente hat.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Typ für Shape thumbnail bounds. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |

### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Klasse [`SummaryZoomFrame`](/slides/python-net/de/aspose.slides/summaryzoomframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)