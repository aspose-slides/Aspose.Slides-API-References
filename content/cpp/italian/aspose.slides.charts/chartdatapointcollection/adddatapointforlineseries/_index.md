---
title: AddDataPointForLineSeries()
second_title: Riferimento API di Aspose.Slides per C++
description: "Crea il nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile alle serie il cui chartType è uno dei sottotipi Line (vedi anche il metodo ChartTypeCharacterizer::IsChartTypeLine(ChartType))."
type: docs
weight: 222
url: /it/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile alle serie il cui chartType è uno dei sottotipi Line (vedi anche il metodo [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valore del punto dati. |

### Valore di ritorno

Nuovo punto dati.

## ChartDataPointCollection::AddDataPointForLineSeries(double) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile alle serie il cui chartType è uno dei sottotipi Line (vedi anche il metodo [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Valore del punto dati. |

### Valore di ritorno

Nuovo punto dati.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)