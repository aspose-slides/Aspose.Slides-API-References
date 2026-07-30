---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova serie di grafico e la aggiunge alla raccolta.
type: docs
weight: 14
url: /it/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metodo


Crea una nuova serie di grafico e la aggiunge alla raccolta.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type of series |

### Valore di ritorno

New chart series.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metodo


Crea una nuova serie di grafico da [IChartDataCell](../../ichartdatacell/) e la aggiunge alla raccolta.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) che contiene il nome della serie. |
| type | [ChartType](../../charttype/) | Tipo impostato della serie |

### Valore di ritorno

Added chart series or series that already is in collection.

## Osservazioni


Se la serie di grafico creata dalla stessa cella è già nella raccolta, il metodo non aggiunge nulla e restituisce il suo indice.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metodo


Crea una nuova serie di grafico da [IChartCellCollection](../../ichartcellcollection/) e la aggiunge alla raccolta.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Celle che contengono il nome della serie. |
| type | [ChartType](../../charttype/) | Tipo impostato della serie |

### Valore di ritorno

Added chart series or series that already is in collection.

## Osservazioni


Se la serie di grafico creata dalla stessa cella è già nella raccolta, il metodo non aggiunge nulla e restituisce il suo indice.



## IChartSeriesCollection::Add(System::String, ChartType) metodo


Crea una nuova serie di grafico dal valore e la aggiunge alla raccolta.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nome della serie. |
| type | [ChartType](../../charttype/) | Tipo impostato della serie |

### Valore di ritorno

Added chart series.



## Vedi anche

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [IChartSeriesCollection](../)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCellCollection](../../ichartcellcollection/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)