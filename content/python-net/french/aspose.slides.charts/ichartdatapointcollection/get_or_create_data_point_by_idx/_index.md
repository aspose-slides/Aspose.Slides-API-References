---
title: get_or_create_data_point_by_idx method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            Si la collection ne contient pas de point de données avec l'index `index`==N
            (lorsque le nombre de points de données dans cette collection est inférieur ou égal à N)
            alors elle ajoute les points de données manquants et renvoie le dernier (qui possède l'index demandé).
            Par exemple, les index de la collection sont {0, 1, 2}, et l'index demandé est 5.
            Ensuite la méthode ajoute les points de données manquants : {0, 1, 2, 3, 4, 5}. Et renvoie le point de données avec l'index 5.

### Renvoie

Renvoie le point de données avec l'index demandé.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Index. |



### Voir aussi
* classe [`IChartDataPoint`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint)
* classe [`IChartDataPointCollection`](/slides/python-net/fr/aspose.slides.charts/ichartdatapointcollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)