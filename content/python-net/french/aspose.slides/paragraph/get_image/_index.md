---
title: get_image method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Retourne une image du paragraphe.

### Retour

Une image contenant le paragraphe rendu, ou **None**
             si le paragraphe ne peut pas être trouvé dans sa collection parente, n'a pas de limites de rendu valides, ou si une erreur se produit lors du rendu de l'image.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Retourne une image du paragraphe avec l'échelle spécifiée.

### Retour

Une image contenant le paragraphe rendu, ou **None**
             si le paragraphe ne peut pas être trouvé dans sa collection parente, n'a pas de limites de rendu valides, ou si une erreur se produit lors du rendu de l'image.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| scale_x | **float** | Le facteur d'échelle horizontal appliqué à l'image du paragraphe. |
| scale_y | **float** | Le facteur d'échelle vertical appliqué à l'image du paragraphe. |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`Paragraph`](/slides/python-net/fr/aspose.slides/paragraph)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)