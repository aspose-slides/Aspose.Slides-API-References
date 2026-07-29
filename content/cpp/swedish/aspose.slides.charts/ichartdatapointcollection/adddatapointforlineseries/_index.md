---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides för C++ API-referens
description: Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Linje-undertyperna (se även ChartTypeCharacterizer.IsChartTypeLine(ChartType) metod).
type: docs
weight: 157
url: /sv/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) metod

Skapar en ny datapunkt och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Linje-undertyperna (se även [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) metod).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktvärde. |

### Returvärde

Ny datapunkt.

## IChartDataPointCollection::AddDataPointForLineSeries(double) metod

Skapar en ny datapunkt och lägger till den i slutet av samlingen. Gäller för serier där chartType är en av Linje-undertyperna (se även [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) metod).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Datapunktvärde. |

### Returvärde

Ny datapunkt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [IChartDataPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)