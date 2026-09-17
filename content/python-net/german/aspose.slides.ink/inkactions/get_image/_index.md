---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Gibt das Form-Thumbnail zurück.
Der Typ ShapeThumbnailBounds.Shape für Shape-Thumbnail-Bereiche wird standardmäßig verwendet.

### Rückgabe

Form-Thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Form-Thumbnail zurück.

### Rückgabe

Form-Thumbnail oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und eine Form keine sichtbaren Elemente besitzt.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Typ des Shape-Thumbnail-Bereichs. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`InkActions`](/slides/python-net/de/aspose.slides.ink/inkactions)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)