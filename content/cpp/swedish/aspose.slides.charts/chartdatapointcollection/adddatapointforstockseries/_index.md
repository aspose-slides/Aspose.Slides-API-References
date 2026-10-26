---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Stock-undertyperna (se även ChartTypeCharacterizer::IsChartTypeStock(ChartType) metod)."
type: docs
weight: 209
url: /sv/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) metod

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Stock-undertyperna (se även [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datapunktvärde. |

### Returvärde

Ny datapunkt.

## ChartDataPointCollection::AddDataPointForStockSeries(double) metod

Skapar den nya datapunkten och lägger till den i slutet av samlingen. Gäller för serier vars chartType är en av Stock-undertyperna (se även [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metod).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Datapunktvärde. |

### Returvärde

Ny datapunkt.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [ChartDataPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)