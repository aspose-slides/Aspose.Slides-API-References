---
title: add method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Ajoute une nouvelle cellule à la collection.


```python
def add(self, cell):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) | Nouvelle cellule à ajouter. |


## add(self, value) {#any}
Crée [`ChartDataCell`](/slides/python-net/fr/aspose.slides.charts/chartdatacell) à partir de la valeur spécifiée et l’ajoute à la collection.


```python
def add(self, value):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| value | **any** | La valeur. |

### Remarques

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs.  Si vous utilisez [`ChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/chartdataworkbook) pour ajouter ou modifier les valeurs des cellules, assurez-vous de ne pas utiliser cette feuille de calcul
Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | si la limite est dépassée |



### Voir aussi
* classe [`ChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/chartcellcollection)
* classe [`ChartDataCell`](/slides/python-net/fr/aspose.slides.charts/chartdatacell)
* classe [`ChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/chartdataworkbook)
* classe [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)