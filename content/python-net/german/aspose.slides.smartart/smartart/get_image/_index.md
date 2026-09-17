---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Gibt das Shape thumbnail zurück.
ShapeThumbnailBounds.Shape shape thumbnail bounds type wird standardmäßig verwendet.

### Rückgabe

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Shape thumbnail zurück.

### Rückgabe

Shape thumbnail oder None, wenn ShapeThumbnailBounds.Appearance verwendet wird und eine Form keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Typ der Shape thumbnail bounds. |
| scale_x | **float** | X-Skalierung |
| scale_y | **float** | Y-Skalierung |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Klasse [`SmartArt`](/slides/python-net/de/aspose.slides.smartart/smartart)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)