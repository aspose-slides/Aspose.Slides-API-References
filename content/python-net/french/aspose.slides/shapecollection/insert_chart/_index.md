---
title: insert_chart method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres,  
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
| index | **int** | L’indice zéro-base où insérer le nouveau graphique dans la collection de formes. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres,  
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
| index | **int** | L’indice zéro-base où insérer le nouveau graphique dans la collection de formes. |
| init_with_sample | **bool** | True pour initialiser le nouveau graphique avec des données d'exemple de séries et des paramètres ; <br/><br/>false pour créer le graphique sans séries et avec uniquement des paramètres minimaux, ce qui accélère la création. |



### Voir aussi
* énumération [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)