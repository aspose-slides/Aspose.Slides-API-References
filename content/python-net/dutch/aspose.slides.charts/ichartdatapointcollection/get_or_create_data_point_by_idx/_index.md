---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Als de collectie al een gegevenspunt met index `index` bevat, wordt dit gegevenspunt geretourneerd.
            Als de collectie geen gegevenspunt met index `index`==N bevat
            (wanneer het aantal gegevenspunten in deze collectie kleiner dan of gelijk aan N is)
            dan worden ontbrekende gegevenspunten toegevoegd en wordt het laatste (met de gevraagde index) geretourneerd.
            Bijvoorbeeld, de indices van de collectie zijn {0, 1, 2}, en de gevraagde index is 5.
            Vervolgens voegt de methode ontbrekende gegevenspunten toe: {0, 1, 2, 3, 4, 5}. En retourneert gegevenspunt met index 5.

### Retourwaarde

Retourneert gegevenspunt met de gevraagde index.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index. |



### Zie ook
* klasse [`IChartDataPoint`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint)
* klasse [`IChartDataPointCollection`](/slides/python-net/nl/aspose.slides.charts/ichartdatapointcollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)