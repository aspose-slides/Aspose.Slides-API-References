---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Column eller Bar under-typer (se även ChartTypeCharacterizer::IsChartTypeColumn(ChartType) och ChartTypeCharacterizer::IsChartTypeBar(ChartType) metod)."
type: docs
weight: 261
url: /sv/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metod


Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av [Column](../../../aspose.slides/column/) eller Bar-undertyper (se även [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) och [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktvärde |

### Returvärde

Ny datapunkt.

## ChartDataPointCollection::AddDataPointForBarSeries(double) metod


Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av [Column](../../../aspose.slides/column/) eller Bar-undertyper (se även [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) och [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Datapunktvärde |

### Returvärde

Ny datapunkt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [ChartDataPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)