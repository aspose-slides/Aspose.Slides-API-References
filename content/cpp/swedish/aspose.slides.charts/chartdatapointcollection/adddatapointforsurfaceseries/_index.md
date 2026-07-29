---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Surface-undertyperna (se också ChartTypeCharacterizer::IsChartTypeSurface(ChartType) metod)."
type: docs
weight: 326
url: /sv/aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries/
---
## ChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) metod

Skapar en ny datapunkt och lägger till den i slutet av kollektionen. Gäller för serier vars chartType är en av Surface-undertyperna (se även [ChartTypeCharacterizer::IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktvärde |

### Returvärde

Ny datapunkt.

## ChartDataPointCollection::AddDataPointForSurfaceSeries(double) metod

Skapar en ny datapunkt och lägger till den i slutet av kollektionen. Gäller för serier vars chartType är en av Surface-undertyperna (se även [ChartTypeCharacterizer::IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForSurfaceSeries(double value) override
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