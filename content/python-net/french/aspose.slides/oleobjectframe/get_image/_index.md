---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/oleobjectframe/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la miniature de la forme.
Le type des limites de la miniature de forme ShapeThumbnailBounds.Shape est utilisé par défaut.

### Renvoie

Miniature de la forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la miniature de la forme.

### Renvoie

Miniature de la forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme ne possède pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type des limites de la miniature de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`OleObjectFrame`](/slides/python-net/fr/aspose.slides/oleobjectframe)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)