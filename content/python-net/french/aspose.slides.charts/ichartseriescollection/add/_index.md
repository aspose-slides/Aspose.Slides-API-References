---
title: add method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Crée une nouvelle série de graphique et l'ajoute à la collection.

### Retour

Nouvelle série de graphique.



```python
def add(self, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type de série |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Crée une nouvelle série de graphique à partir de [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) et l'ajoute à la collection.

### Retour

Série de graphique ajoutée ou série déjà présente dans la collection.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) | Cellule contenant le nom de la série. |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type du type de la série |

### Remarques

Si une série de graphique créée à partir de la même cellule est déjà dans la collection, la méthode n'ajoute rien et renvoie son indice.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Crée une nouvelle série de graphique à partir de [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection) et l'ajoute à la collection.

### Retour

Série de graphique ajoutée ou série déjà présente dans la collection.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection) | Cellules contenant le nom de la série. |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type du type de la série |

### Remarques

Si une série de graphique créée à partir de la même cellule est déjà dans la collection, la méthode n'ajoute rien et renvoie son indice.


## add(self, name, type) {#str-charttype}
Crée une nouvelle série de graphique à partir d'une valeur et l'ajoute à la collection.

### Retour

Série de graphique ajoutée.



```python
def add(self, name, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| name | **str** | Nom de la série. |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type du type de la série |



### Voir aussi
* énumération [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype)
* classe [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell)
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* classe [`IChartSeriesCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriescollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)