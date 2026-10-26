---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Als de collectie al een gegevenspunt met index `index` bevat, retourneert deze het gegevenspunt.  
Als de collectie geen gegevenspunt met index `index`==N bevat (wanneer het aantal gegevenspunten in deze collectie minder of gelijk is aan N), voegt het ontbrekende gegevenspunten toe en retourneert het laatste (dat de gevraagde index heeft).  
Bijvoorbeeld, de indexen van de collectie zijn {0, 1, 2}, en de gevraagde index is 5. De methode voegt dan ontbrekende gegevenspunten toe: {0, 1, 2, 3, 4, 5}. En retourneert het gegevenspunt met index 5.

### Retour

Retourneert het gegevenspunt met de gevraagde index.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index. |



### Zie ook
* klasse [`ChartDataPointCollection`](/slides/python-net/nl/aspose.slides.charts/chartdatapointcollection)
* klasse [`IChartDataPoint`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)