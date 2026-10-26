---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Wenn die Sammlung bereits einen Datenpunkt mit dem Index `index` enthält, gibt sie diesen Datenpunkt zurück.
            Wenn die Sammlung keinen Datenpunkt mit dem Index `index`==N enthält (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist), dann werden fehlende Datenpunkte hinzugefügt und der letzte zurückgegeben (der den angeforderten Index hat).
            Zum Beispiel sind die Sammlungsindizes {0, 1, 2} und der angeforderte Index ist 5.
            Dann fügt die Methode fehlende Datenpunkte hinzu: {0, 1, 2, 3, 4, 5}. Und gibt den Datenpunkt mit Index 5 zurück.

### Rückgabewert

Gibt den Datenpunkt mit dem angeforderten Index zurück.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index. |



### Siehe auch
* Klasse [`ChartDataPointCollection`](/slides/python-net/de/aspose.slides.charts/chartdatapointcollection)
* Klasse [`IChartDataPoint`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)