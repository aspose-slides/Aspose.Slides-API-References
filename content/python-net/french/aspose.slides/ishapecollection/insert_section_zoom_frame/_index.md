---
title: insert_section_zoom_frame method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Crée un nouveau cadre Section Zoom et l’insère dans la collection de formes à l’index spécifié.

### Renvoie

Le [`ISectionZoomFrame`](/slides/python-net/fr/aspose.slides/isectionzoomframe) nouvellement créé.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L’indice basé sur zéro à l’endroit où insérer le cadre Section Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Section Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Section Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Section Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Section Zoom, en points. |
| section | [`ISection`](/slides/python-net/fr/aspose.slides/isection) | Le [`ISection`](/slides/python-net/fr/aspose.slides/isection) référencé par le cadre Section Zoom ;<br/><br/>            doit appartenir à cette présentation et contenir au moins une diapositive. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée si la section référencée n’appartient pas à la présentation actuelle ou ne contient aucune diapositive. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Crée un nouveau cadre Section Zoom avec une image prédéfinie et l’insère dans la collection de formes à l’index spécifié.

### Renvoie

Le [`ISectionZoomFrame`](/slides/python-net/fr/aspose.slides/isectionzoomframe) nouvellement créé.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L’indice basé sur zéro à l’endroit où insérer le cadre Section Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Section Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Section Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Section Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Section Zoom, en points. |
| section | [`ISection`](/slides/python-net/fr/aspose.slides/isection) | Le [`ISection`](/slides/python-net/fr/aspose.slides/isection) référencé par le cadre Section Zoom ;<br/><br/>            doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) | L’image à afficher dans le cadre Section Zoom. |

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