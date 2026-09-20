---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Om samlingen redan innehåller en datapunkt med index `index` returnerar den här datapunkten.
            Om samlingen inte innehåller en datapunkt med index `index`==N
            (när antalet datapunkter i denna samling är mindre än eller lika med N)
            lägger den till saknade datapunkter och returnerar den sista (som har det begärda indexet).
            Till exempel är samlingens index {0, 1, 2}, och det begärda indexet är 5.
            Då lägger metoden till saknade datapunkter: {0, 1, 2, 3, 4, 5}. Och returnerar datapunkten med index 5.

### Returnerar

Returnerar datapunkt med det begärda indexet.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index. |



### Se även
* klass [`ChartDataPointCollection`](/slides/python-net/sv/aspose.slides.charts/chartdatapointcollection)
* klass [`IChartDataPoint`](/slides/python-net/sv/aspose.slides.charts/ichartdatapoint)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)