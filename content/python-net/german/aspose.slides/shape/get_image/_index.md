---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
Gibt die Formvorschau zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet.

### Rückgabe

Formvorschau.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt die Formvorschau zurück.

### Rückgabe

Formvorschau oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Typ für die Formvorschau-Grenzen. |
| scale_x | **float** | X-Skalierung |
| scale_y | **float** | Y-Skalierung |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)