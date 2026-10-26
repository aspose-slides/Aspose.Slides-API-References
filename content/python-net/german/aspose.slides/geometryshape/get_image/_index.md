---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
Gibt das Shape-Miniaturbild zurück.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Rückgabe

Shape-Miniaturbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Shape-Miniaturbild zurück.

### Rückgabe

Shape-Miniaturbild oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und das Shape keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Shape-Miniaturbild-Grenztyp. |
| scale_x | **float** | X-Skalierung |
| scale_y | **float** | Y-Skalierung |



### Siehe auch
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)