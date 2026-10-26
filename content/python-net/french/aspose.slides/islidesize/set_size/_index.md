---
title: set_size method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Définit la taille de la diapositive par type et ajuste le contenu existant.


```python
def set_size(self, type, scale_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/fr/aspose.slides/slidesizetype) | La taille de diapositive prédéfinie à appliquer. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/fr/aspose.slides/slidesizescaletype) | Le mode de mise à l'échelle du contenu à utiliser. |

### Remarks

Attribuer toute valeur différente de [`SlideSizeType.CUSTOM`](/slides/python-net/fr/aspose.slides/slidesizetype/CUSTOM) ajuste le [`ISlideSize.size`](/slides/python-net/fr/aspose.slides/islidesize/size) en fonction du type sélectionné, tout en préservant le [`ISlideSize.orientation`](/slides/python-net/fr/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Définit explicitement les dimensions de la diapositive et ajuste le contenu existant.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| width | **float** | La nouvelle largeur de la diapositive, en points. |
| height | **float** | La nouvelle hauteur de la diapositive, en points. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/fr/aspose.slides/slidesizescaletype) | Le mode de mise à l'échelle du contenu à utiliser. |

### Remarks

Cela réinitialise la propriété [`ISlideSize.type`](/slides/python-net/fr/aspose.slides/islidesize/type) à [`SlideSizeType.CUSTOM`](/slides/python-net/fr/aspose.slides/slidesizetype/CUSTOM) et définit le [`ISlideSize.orientation`](/slides/python-net/fr/aspose.slides/islidesize/orientation).



### Voir aussi
* classe [`ISlideSize`](/slides/python-net/fr/aspose.slides/islidesize)
* énumération [`SlideSizeScaleType`](/slides/python-net/fr/aspose.slides/slidesizescaletype)
* énumération [`SlideSizeType`](/slides/python-net/fr/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)