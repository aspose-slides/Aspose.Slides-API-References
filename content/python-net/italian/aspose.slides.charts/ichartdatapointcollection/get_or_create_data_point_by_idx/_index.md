---
title: get_or_create_data_point_by_idx method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Se la collezione contiene già un punto dati con indice `index` allora restituisce questo punto dati.
            Se la collezione non contiene un punto dati con indice `index`==N (quando il numero di punti dati in questa collezione è inferiore o uguale a N) allora aggiunge i punti dati mancanti e restituisce l'ultimo (che ha l'indice richiesto).
            Ad esempio, gli indici della collezione sono {0, 1, 2} e l'indice richiesto è 5.
            Allora il metodo aggiunge i punti dati mancanti: {0, 1, 2, 3, 4, 5}. E restituisce il punto dati con indice 5.

### Restituisce

Restituisce il punto dati con indice richiesto.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice. |



### Vedi anche
* classe [`IChartDataPoint`](/slides/python-net/it/aspose.slides.charts/ichartdatapoint)
* classe [`IChartDataPointCollection`](/slides/python-net/it/aspose.slides.charts/ichartdatapointcollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)