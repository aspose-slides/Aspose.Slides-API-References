---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides a Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Ha a gyűjtemény már tartalmaz adatpontot a `index` indexszel, akkor visszaadja ezt az adatpontot.
            Ha a gyűjtemény nem tartalmaz adatpontot a `index`==N indexszel
            (amikor a gyűjtemény adatpontjainak száma kisebb vagy egyenlő N-nél)
            akkor hozzáadja a hiányzó adatpontokat, és visszaadja az utolsót (amelyik a kért indexű).
            Például a gyűjtemény indexei {0, 1, 2}, és a kért index 5.
            Ekkor a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az adatpontot a 5-ös indexszel.

### Visszatérési érték

Visszaadja a kért indexű adatpontot.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Index. |



### Lásd még
* osztály [`ChartDataPointCollection`](/slides/python-net/hu/aspose.slides.charts/chartdatapointcollection)
* osztály [`IChartDataPoint`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)