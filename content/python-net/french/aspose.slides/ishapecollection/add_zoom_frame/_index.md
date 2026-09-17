---
title: add_zoom_frame method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Crée un nouveau Zoom frame et l'ajoute à la fin de la collection de formes.

### Retour

Le [`IZoomFrame`](/slides/python-net/fr/aspose.slides/izoomframe) nouvellement créé.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau Zoom frame, en points. |
| y | **float** | La coordonnée y du nouveau Zoom frame, en points. |
| width | **float** | La largeur du nouveau Zoom frame, en points. |
| height | **float** | La hauteur du nouveau Zoom frame, en points. |
| slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Le [`ISlide`](/slides/python-net/fr/aspose.slides/islide) référencé par le Zoom frame;<br/><br/>            doit appartenir à cette présentation. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si la diapositive référencée n'appartient pas à la présentation actuelle. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Crée un nouveau Zoom frame et l'ajoute à la fin de la collection de formes.

### Retour

Le [`IZoomFrame`](/slides/python-net/fr/aspose.slides/izoomframe) nouvellement créé.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau Zoom frame, en points. |
| y | **float** | La coordonnée y du nouveau Zoom frame, en points. |
| width | **float** | La largeur du nouveau Zoom frame, en points. |
| height | **float** | La hauteur du nouveau Zoom frame, en points. |
| slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Le [`ISlide`](/slides/python-net/fr/aspose.slides/islide) référencé par le Zoom frame;<br/><br/>            doit appartenir à cette présentation. |
| image | [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) | L'image pour la diapositive référencée [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si la diapositive référencée n'appartient pas à la présentation actuelle. |



### Voir aussi
* classe [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`IZoomFrame`](/slides/python-net/fr/aspose.slides/izoomframe)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)