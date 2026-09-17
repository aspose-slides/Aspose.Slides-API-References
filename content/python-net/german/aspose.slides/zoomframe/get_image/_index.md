---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Gibt die Form-Miniatur zurück.  
ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Form-Miniatur-Grenzen verwendet.

### Rückgabe

Form-Miniatur.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt die Form-Miniatur zurück.

### Rückgabe

Form-Miniatur oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente enthält.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Typ für Form-Miniatur-Grenzen. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Klasse [`ZoomFrame`](/slides/python-net/de/aspose.slides/zoomframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)