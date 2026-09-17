---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Gibt das Shape-Vorschaubild zurück. Der ShapeThumbnailBounds.Shape Shape-Vorschaubereichstyp wird standardmäßig verwendet.

### Rückgabewert

Shape-Vorschaubild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Shape-Vorschaubild zurück.

### Rückgabewert

Shape-Vorschaubild oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und ein Shape keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Shape-Vorschaubereichstyp. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |



### Siehe auch
* Klasse [`AudioFrame`](/slides/python-net/de/aspose.slides/audioframe)
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)