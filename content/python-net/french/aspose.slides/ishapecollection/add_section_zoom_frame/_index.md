---
title: add_section_zoom_frame method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Crée un nouveau cadre Section Zoom et l’ajoute à la fin de la collection de formes.

### Renvoie

Le [`ISectionZoomFrame`](/slides/python-net/fr/aspose.slides/isectionzoomframe) nouvellement créé.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre Section Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Section Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Section Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Section Zoom, en points. |
| section | [`ISection`](/slides/python-net/fr/aspose.slides/isection) | Le [`ISection`](/slides/python-net/fr/aspose.slides/isection) référencé par le cadre Section Zoom;<br/><br/> doit appartenir à cette présentation et contenir au moins une diapositive. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée si la section référencée n’appartient pas à la présentation actuelle ou ne contient aucune diapositive. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Crée un nouveau cadre Section Zoom avec une image prédéfinie et l’ajoute à la fin de la collection de formes.

### Renvoie

Le [`ISectionZoomFrame`](/slides/python-net/fr/aspose.slides/isectionzoomframe) nouvellement créé.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre Section Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Section Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Section Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Section Zoom, en points. |
| section | [`ISection`](/slides/python-net/fr/aspose.slides/isection) | Le [`ISection`](/slides/python-net/fr/aspose.slides/isection) référencé par le cadre Section Zoom;<br/><br/> doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) | Le [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) à afficher dans le cadre Section Zoom. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée si la section référencée n’appartient pas à la présentation actuelle ou ne contient aucune diapositive. |



### Voir aussi
* classe [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage)
* classe [`ISection`](/slides/python-net/fr/aspose.slides/isection)
* classe [`ISectionZoomFrame`](/slides/python-net/fr/aspose.slides/isectionzoomframe)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)