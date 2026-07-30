---
title: AddDataPointForStockSeries()
second_title: Riferimento API Aspose.Slides per C++
description: "Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile per le serie il cui chartType è uno dei sottotipi Stock (vedi anche il metodo ChartTypeCharacterizer::IsChartTypeStock(ChartType))."
type: docs
weight: 209
url: /it/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile per le serie il cui chartType è uno dei sottotipi Stock (vedi anche [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metodo).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valore del punto dati. |

### Valore restituito

Nuovo punto dati.

## ChartDataPointCollection::AddDataPointForStockSeries(double) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile per le serie il cui chartType è uno dei sottotipi Stock (vedi anche [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metodo).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Valore del punto dati. |

### Valore restituito

Nuovo punto dati.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)