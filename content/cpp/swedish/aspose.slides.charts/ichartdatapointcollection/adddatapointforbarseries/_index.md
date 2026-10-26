---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides för C++ API-referens
description: Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Column eller Bar-undertyper (se även ChartTypeCharacterizer.IsChartTypeColumn(ChartType) och ChartTypeCharacterizer.IsChartTypeBar(ChartType) metod).
type: docs
weight: 196
url: /sv/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metod

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av [Column](../../../aspose.slides/column/) eller Bar-undertyper (se även [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) och [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metod).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktens värde |

### Returvärde

Ny datapunkt.

## IChartDataPointCollection::AddDataPointForBarSeries(double) metod

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av [Column](../../../aspose.slides/column/) eller Bar-undertyper (se även [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) och [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metod).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | Datapunktens värde |

### Returvärde

Ny datapunkt.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [IChartDataPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)