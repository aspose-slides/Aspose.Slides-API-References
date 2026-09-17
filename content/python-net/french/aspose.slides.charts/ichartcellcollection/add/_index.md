---
title: add method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Ajoute une nouvelle cellule à la collection.


```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) | Nouvelle cellule à ajouter. |


## add(self, value) {#any}
Crée [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) à partir de la valeur spécifiée et l'ajoute à la collection.


```python
def add(self, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| value | **any** | La valeur. |

### Remarques

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs.  Si vous utilisez [`IChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/ichartdataworkbook) pour ajouter ou modifier des valeurs de Cell, assurez-vous de ne pas utiliser cette feuille de calcul
            Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | if limit exceeded |



### Voir aussi
* classe [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell)
* classe [`IChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)