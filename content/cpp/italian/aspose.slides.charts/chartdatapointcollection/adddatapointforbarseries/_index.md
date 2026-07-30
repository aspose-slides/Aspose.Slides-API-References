---
title: AddDataPointForBarSeries()
second_title: Riferimento API Aspose.Slides per C++
description: "Crea il nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile per le serie il cui chartType è uno dei sottotipi Column o Bar (vedi anche ChartTypeCharacterizer::IsChartTypeColumn(ChartType) e ChartTypeCharacterizer::IsChartTypeBar(ChartType) metodo)."
type: docs
weight: 261
url: /it/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metodo


Crea un nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile per le serie il cui chartType è uno dei [Column](../../../aspose.slides/column/) o sottotipi Bar (vedi anche [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) e [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodo).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valore del punto dati |

### Valore di ritorno

Nuovo punto dati.

## ChartDataPointCollection::AddDataPointForBarSeries(double) metodo


Crea un nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile per le serie il cui chartType è uno dei [Column](../../../aspose.slides/column/) o sottotipi Bar (vedi anche [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) e [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodo).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Valore del punto dati |

### Valore di ritorno

Nuovo punto dati.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartDataPointCollection](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)