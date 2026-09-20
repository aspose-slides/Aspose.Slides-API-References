---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Se la raccolta contiene già un punto dati con indice `index`, restituisce questo punto dati.
            Se la raccolta non contiene un punto dati con indice `index`==N (quando il numero di punti dati in questa raccolta è minore o uguale a N), aggiunge i punti dati mancanti e restituisce l'ultimo (che ha l'indice richiesto).
            Ad esempio, gli indici della raccolta sono {0, 1, 2} e l'indice richiesto è 5.
            Quindi il metodo aggiunge i punti dati mancanti: {0, 1, 2, 3, 4, 5}. E restituisce il punto dati con indice 5.

### Restituisce

Restituisce il punto dati con l'indice richiesto.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice. |



### Vedi anche
* classe [`ChartDataPointCollection`](/slides/python-net/it/aspose.slides.charts/chartdatapointcollection)
* classe [`IChartDataPoint`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)