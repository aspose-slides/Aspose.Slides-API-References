---
title: insert_chart method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres,
            et l'insère dans la collection de formes à l'index spécifié.

### Retour

Le [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) nouvellement créé.



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Le type de graphique à créer. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du nouveau graphique, en points. |
| height | **float** | La hauteur du nouveau graphique, en points. |
| index | **int** | L'index zéro basé auquel insérer le nouveau graphique dans la collection de formes. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres,
            et l'insère dans la collection de formes à l'index spécifié.

### Retour

Le [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) nouvellement créé.



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Le type de graphique à créer. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du nouveau graphique, en points. |
| height | **float** | La hauteur du nouveau graphique, en points. |
| index | **int** | L'index zéro basé auquel insérer le nouveau graphique dans la collection de formes. |
| init_with_sample | **bool** | True pour initialiser le nouveau graphique avec des données de séries d'exemple et des paramètres ; <br/><br/>            false pour créer le graphique sans séries et uniquement avec des paramètres minimaux, ce qui rend la création plus rapide. |



### Voir aussi
* énumération [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)