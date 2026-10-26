---
title: add method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/chartseriescollection/add/
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
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type de la série |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Crée une nouvelle série de graphique à partir de [`ChartDataCell`](/slides/python-net/fr/aspose.slides.charts/chartdatacell) et l'ajoute à la collection.

### Retour

Série de graphique ajoutée ou série déjà présente dans la collection.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) | Cellule contenant le nom de la série. |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type définissant le type de la série |

### Remarques

Si la série de graphique créée à partir de la même cellule est déjà dans la collection, la méthode n'ajoute rien et renvoie son indice.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Crée une nouvelle série de graphique à partir de [`ChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/chartcellcollection) et l'ajoute à la collection.

### Retour

Série de graphique ajoutée ou série déjà présente dans la collection.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection) | Cellules contenant le nom de la série. |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type définissant le type de la série |

### Remarques

Si la série de graphique créée à partir de la même cellule est déjà dans la collection, la méthode n'ajoute rien et renvoie son indice.


## add(self, name, type) {#str-charttype}
Crée une nouvelle série de graphique à partir de la valeur et l'ajoute à la collection.

### Retour

Série de graphique ajoutée.



```python
def add(self, name, type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| name | **str** | Nom de la série. |
| type | [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype) | Type définissant le type de la série |



### Voir aussi
* classe [`ChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/chartcellcollection)
* classe [`ChartDataCell`](/slides/python-net/fr/aspose.slides.charts/chartdatacell)
* classe [`ChartSeriesCollection`](/slides/python-net/fr/aspose.slides.charts/chartseriescollection)
* énumération [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype)
* classe [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell)
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)