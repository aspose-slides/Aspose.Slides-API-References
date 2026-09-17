---
title: add method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
If category exists in collection, return it. Else creates new chart category from 
            [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) and adds it to the collection.

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
Creates new [`ChartCategory`](/slides/python-net/fr/aspose.slides.charts/chartcategory) from value and adds it to the collection.

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

This method adds worksheet with name AUTO_DATA and adds all values there.  If you use [`ChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/chartdataworkbook) to add or edit cell values, be sure that you do not use this worksheet
            Maximum number of values added using this method must not exceed 16711680

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | si la limite est dépassée |



### Voir aussi
* classe [`ChartCategory`](/slides/python-net/fr/aspose.slides.charts/chartcategory)
* classe [`ChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection)
* classe [`ChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/chartdataworkbook)
* classe [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory)
* classe [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)