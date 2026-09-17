---
title: insert_zoom_frame method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié.

### Renvoie

Le [`IZoomFrame`](/slides/python-net/fr/aspose.slides/izoomframe) nouvellement créé.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro où insérer le cadre Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Le [`ISlide`](/slides/python-net/fr/aspose.slides/islide) référencé par le cadre Zoom. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si la diapositive référencée n'appartient pas à la présentation actuelle. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié.

### Renvoie

Le [`IZoomFrame`](/slides/python-net/fr/aspose.slides/izoomframe) nouvellement créé.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro où insérer le cadre Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Le [`ISlide`](/slides/python-net/fr/aspose.slides/islide) référencé par le cadre Zoom. |
| image | [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) | L'image pour la diapositive référencée [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si la diapositive référencée n'appartient pas à la présentation actuelle. |



### Voir aussi
* classe [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`IZoomFrame`](/slides/python-net/fr/aspose.slides/izoomframe)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)