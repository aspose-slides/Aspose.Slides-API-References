---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Gibt das Shape-Vorschaubild zurück.
            Der Typ ShapeThumbnailBounds.Shape shape thumbnail bounds wird standardmäßig verwendet.

### Rückgabe

Shape-Vorschaubild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Shape-Vorschaubild zurück.

### Rückgabe

Shape-Vorschaubild oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und ein Shape keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |



### Siehe auch
* Klasse [`GroupShape`](/slides/python-net/de/aspose.slides/groupshape)
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)