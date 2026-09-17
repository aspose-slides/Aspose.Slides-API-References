---
title: add method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Si la catégorie existe dans la collection, la renvoie. Sinon crée une nouvelle catégorie de graphique à partir de [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) et l’ajoute à la collection.

### Renvoie

Catégorie ajoutée ou existante.



```python
def add(self, chart_data_cell):
    ...
```



| Paramètre | Type | Description |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) | Cell used to create chart category. |


## add(self, value) {#any}
Crée un nouveau [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory) à partir de la valeur et l’ajoute à la collection.

### Renvoie

Ajouté [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| value | **any** | The value. |

### Remarques

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs.  Si vous utilisez [`IChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/ichartdataworkbook) pour ajouter ou modifier des valeurs de cellules, assurez-vous de ne pas utiliser cette feuille de calcul
            Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | si la limite est dépassée |



### Voir aussi
* classe [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory)
* classe [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell)
* classe [`IChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)