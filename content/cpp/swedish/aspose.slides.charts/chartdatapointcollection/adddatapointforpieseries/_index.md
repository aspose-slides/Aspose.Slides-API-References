---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Pie undertyperna (se även ChartTypeCharacterizer::IsChartTypePie(ChartType) metod)."
type: docs
weight: 287
url: /sv/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) metod


Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Pie-undertyperna (se även [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktvärde |

### Returvärde

Ny datapunkt.

## ChartDataPointCollection::AddDataPointForPieSeries(double) metod


Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Pie-undertyperna (se även [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
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
* Bibliotek [Aspose.Slides](../../../)