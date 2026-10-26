---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním ze Stock podtypů (viz také metoda ChartTypeCharacterizer::IsChartTypeStock(ChartType))."
type: docs
weight: 209
url: /cs/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) metoda

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním ze Stock podtypů (viz také [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metoda).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Hodnota datového bodu. |

### Návratová hodnota

Nový datový bod.

## ChartDataPointCollection::AddDataPointForStockSeries(double) metoda

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním ze Stock podtypů (viz také [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metoda).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota datového bodu. |

### Návratová hodnota

Nový datový bod.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataPoint](../../ichartdatapoint/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [ChartDataPointCollection](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)