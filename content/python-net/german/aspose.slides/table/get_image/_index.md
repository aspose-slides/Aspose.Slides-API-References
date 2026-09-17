---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
Gibt die Shape Miniaturansicht zurück.
Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet.

### Rückgabe

Shape Miniaturansicht.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt die Shape Miniaturansicht zurück.

### Rückgabe

Shape Miniaturansicht oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und ein Shape keine sichtbaren Elemente hat.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds Typ. |
| scale_x | **float** | X-Skalierung |
| scale_y | **float** | Y-Skalierung |

### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Klasse [`Table`](/slides/python-net/de/aspose.slides/table)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)