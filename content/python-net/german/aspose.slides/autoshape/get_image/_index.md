---
title: get_image method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Gibt das Shape-Thumbnail zurück.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type wird standardmäßig verwendet.

### Rückgabewert

Shape-Vorschaubild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Shape-Thumbnail zurück.

### Rückgabewert

Shape thumbnail oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und ein Shape keine sichtbaren Elemente besitzt.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X Skala |
| scale_y | **float** | Y Skala |



### Siehe auch
* Klasse [`AutoShape`](/slides/python-net/de/aspose.slides/autoshape)
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)