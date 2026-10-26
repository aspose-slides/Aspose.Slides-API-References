---
title: add_chart method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes.

### Renvoie

Le [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) nouvellement créé.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Le type de graphique à ajouter. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du graphique, en points. |
| height | **float** | La hauteur du graphique, en points. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes.

### Renvoie

Le [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) nouvellement créé.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Le type de graphique à ajouter. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du graphique, en points. |
| height | **float** | La hauteur du graphique, en points. |
| init_with_sample | **bool** | True pour initialiser le nouveau graphique avec des données de séries d'exemple et des paramètres ; <br/><br/>            false pour créer le graphique sans séries et uniquement avec des paramètres minimaux, ce qui rend la création<br/><br/>            plus rapide. |



### Voir également
* énumération [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)