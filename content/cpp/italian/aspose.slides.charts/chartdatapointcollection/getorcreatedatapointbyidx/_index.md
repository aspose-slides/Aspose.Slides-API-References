---
title: GetOrCreateDataPointByIdx()
second_title: Riferimento API di Aspose.Slides per C++
description: "Se la collezione contiene già un punto dati con indice index restituisce questo punto dati. Se la collezione non contiene un punto dati con indice index ==N (quando il numero di punti dati in questa collezione è minore o uguale a N) allora aggiunge i punti dati mancanti e restituisce l'ultimo (che ha l'indice richiesto). Per esempio, gli indici della collezione sono {0, 1, 2} e l'indice richiesto è 5. Allora il metodo aggiunge i punti dati mancanti: {0, 1, 2, 3, 4, 5}. E restituisce il punto dati con indice 5."
type: docs
weight: 170
url: /it/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metodo

Se la collezione contiene già un punto dati con indice *index* restituisce questo punto dati. Se la collezione non contiene un punto dati con indice *index* ==N (quando il numero di punti dati in questa collezione è minore o uguale a N) allora aggiunge i punti dati mancanti e restituisce l'ultimo (che ha l'indice richiesto). Per esempio, gli indici della collezione sono {0, 1, 2}, e l'indice richiesto è 5. Allora il metodo aggiunge i punti dati mancanti: {0, 1, 2, 3, 4, 5}. E restituisce il punto dati con indice 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **uint32_t** | Indice. |

### Valore di ritorno

Restituisce il punto dati con l'indice richiesto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)