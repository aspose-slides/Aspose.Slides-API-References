---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Gibt das Form-Vorschaubild zurück.
            ShapeThumbnailBounds.Shape Form-Vorschaubild-Grenztyp wird standardmäßig verwendet.

### Rückgabewert

Form-Vorschaubild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Gibt das Form-Vorschaubild zurück.

### Rückgabewert

Form-Vorschaubild oder None, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente hat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds) | Form-Vorschaubild-Grenztyp. |
| scale_x | **float** | X-Skala |
| scale_y | **float** | Y-Skala |



### Siehe auch
* class [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/de/aspose.slides/shapethumbnailbounds)
* class [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)