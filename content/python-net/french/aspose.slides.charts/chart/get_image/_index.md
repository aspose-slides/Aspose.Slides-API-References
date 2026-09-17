---
title: get_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
Renvoie la vignette de forme.
            Le type de limites de vignette de forme ShapeThumbnailBounds.Shape est utilisé par défaut.

### Renvoie

Vignette de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette de forme.

### Renvoie

Vignette de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme ne possède pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type de limites de vignette de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* class [`Chart`](/slides/python-net/fr/aspose.slides.charts/chart)
* class [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)