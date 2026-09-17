---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Gibt das Shape thumbnail zurück.  
Der Typ ShapeThumbnailBounds.Shape für Shape thumbnail bounds wird standardmäßig verwendet.

### Rückgabe

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Shape thumbnail zurück.

### Rückgabe

Shape thumbnail oder None, wenn ShapeThumbnailBounds.Appearance verwendet wird und eine Form keine sichtbaren Elemente enthält.



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
* Klasse [`SectionZoomFrame`](/slides/python-net/de/aspose.slides/sectionzoomframe)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)