---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Gibt das Form-Miniaturbild zurück.
            ShapeThumbnailBounds.Shape Der Typ der Form-Miniaturbildgrenzen wird standardmäßig verwendet.

### Rückgabe

Form-Miniaturbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Form-Miniaturbild zurück.

### Rückgabe

Form-Miniaturbild oder None, wenn ShapeThumbnailBounds.Appearance verwendet wird und eine Form keine sichtbaren Elemente hat.



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
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`Ink`](/slides/python-net/de/aspose.slides.ink/ink)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)