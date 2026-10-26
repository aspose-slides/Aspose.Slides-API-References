---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Stock (viz také metodu ChartTypeCharacterizer.IsChartTypeStock(ChartType)).
type: docs
weight: 144
url: /cs/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) metoda

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Stock (viz také [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metoda).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Hodnota datového bodu. |

### Návratová hodnota

Nový datový bod.

## IChartDataPointCollection::AddDataPointForStockSeries(double) metoda

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Stock (viz také [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metoda).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
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
* Třída [IChartDataPointCollection](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)