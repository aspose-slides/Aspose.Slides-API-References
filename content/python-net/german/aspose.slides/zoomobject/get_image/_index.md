---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
Gibt das Form-Vorschaubild zurück.  
ShapeThumbnailBounds.Shape wird standardmäßig als Typ für Form-Vorschaubild-Grenzen verwendet.

### Rückgabe

Form-Vorschaubild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Form-Vorschaubild zurück.

### Rückgabe

Form-Vorschaubild oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Typ des Form-Vorschaubild-Grenztyps. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Klasse [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)