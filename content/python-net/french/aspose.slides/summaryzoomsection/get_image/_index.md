---
title: get_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la vignette de forme.
            Le type ShapeThumbnailBounds.Shape est utilisé par défaut.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type des limites de la vignette de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* classe [`SummaryZoomSection`](/slides/python-net/fr/aspose.slides/summaryzoomsection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)