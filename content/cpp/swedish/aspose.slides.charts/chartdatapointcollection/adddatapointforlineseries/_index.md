---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Line-undertyperna (se även ChartTypeCharacterizer::IsChartTypeLine(ChartType) metod)."
type: docs
weight: 222
url: /sv/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) metod

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Line-undertyperna (se även [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktens värde. |

### Returvärde

Ny datapunkt.

## ChartDataPointCollection::AddDataPointForLineSeries(double) metod

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Line-undertyperna (se även [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Datapunktens värde. |

### Returvärde

Ny datapunkt.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [ChartDataPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)