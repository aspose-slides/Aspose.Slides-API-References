---
title: get_image method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/ishape/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la miniature de forme.  
ShapeThumbnailBounds.Shape type de limites de miniature de forme est utilisé par défaut.

### Retour

Miniature de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la miniature de forme.

### Retour

Miniature de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu’une forme ne possède pas d’éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type de limites de la miniature de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)