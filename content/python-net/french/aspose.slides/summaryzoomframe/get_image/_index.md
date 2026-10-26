---
title: get_image method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/summaryzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie une miniature de forme.  
ShapeThumbnailBounds.Shape est le type de limites de miniature de forme utilisé par défaut.

### Valeur de retour

Miniature de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie une miniature de forme.

### Valeur de retour

Miniature de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu’une forme ne possède pas d’éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type de limites de miniature de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* classe [`SummaryZoomFrame`](/slides/python-net/fr/aspose.slides/summaryzoomframe)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)