---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova serie di grafico e la aggiunge alla collezione.
type: docs
weight: 53
url: /it/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) metodo


Crea una nuova serie del grafico e la aggiunge alla collezione.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipo della serie |

### Valore restituito

Nuova serie del grafico.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metodo


Crea una nuova serie del grafico da [ChartDataCell](../../chartdatacell/) e la aggiunge alla collezione.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) che contiene il nome della serie. |
| type | [ChartType](../../charttype/) | Tipo impostato del tipo di serie |

### Valore restituito

Serie del grafico aggiunta o serie già presente nella collezione.

## Note


Se la serie del grafico creata dalla stessa cella è già nella collezione, il metodo non aggiunge nulla e restituisce il suo indice.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metodo


Crea una nuova serie del grafico da [ChartCellCollection](../../chartcellcollection/) e la aggiunge alla collezione.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Celle che contengono il nome della serie. |
| type | [ChartType](../../charttype/) | Tipo impostato del tipo di serie |

### Valore restituito

Serie del grafico aggiunta o serie già presente nella collezione.

## Note


Se la serie del grafico creata dalla stessa cella è già nella collezione, il metodo non aggiunge nulla e restituisce il suo indice.



## ChartSeriesCollection::Add(System::String, ChartType) metodo


Crea una nuova serie del grafico a partire da un valore e la aggiunge alla collezione.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nome della serie. |
| type | [ChartType](../../charttype/) | Tipo impostato del tipo di serie |

### Valore restituito

Serie del grafico aggiunta.



## Vedi anche

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [ChartSeriesCollection](../)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCellCollection](../../ichartcellcollection/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)