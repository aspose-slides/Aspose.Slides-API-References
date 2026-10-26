---
title: AddDataPointForBarSeries()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Column o Bar (vedi anche ChartTypeCharacterizer.IsChartTypeColumn(ChartType) e ChartTypeCharacterizer.IsChartTypeBar(ChartType) metodo).
type: docs
weight: 196
url: /it/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno di [Column](../../../aspose.slides/column/) o sottotipi Bar (vedi anche [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) e [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodi).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### Valore di ritorno

Nuovo punto dati.

## IChartDataPointCollection::AddDataPointForBarSeries(double) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno di [Column](../../../aspose.slides/column/) o sottotipi Bar (vedi anche [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) e [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodi).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Data point Value |

### Valore di ritorno

Nuovo punto dati.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)