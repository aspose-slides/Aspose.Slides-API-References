---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'elemento dalla raccolta.
type: docs
weight: 79
url: /it/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) metodo

Rimuove l'elemento dalla raccolta.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Punto dati da rimuovere. |

### Valore restituito

true se l'elemento è stato rimosso correttamente; altrimenti, false. Questo metodo restituisce anche false se l'elemento non è stato trovato in [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) metodo

Rimuove l'elemento dalla raccolta tramite il suo indice nella raccolta di punti della serie padre.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Indice del punto dati nella raccolta di punti della serie padre. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)