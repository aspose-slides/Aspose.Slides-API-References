---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides pro C++ - reference API
description: "Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z podtypů Column nebo Bar (viz také ChartTypeCharacterizer::IsChartTypeColumn(ChartType) a ChartTypeCharacterizer::IsChartTypeBar(ChartType) method)."
type: docs
weight: 261
url: /cs/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metoda

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z [Column](../../../aspose.slides/column/) nebo podtypy Bar (viz také [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) a [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metoda).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Hodnota datového bodu |

### Návratová hodnota

Nový datový bod.

## ChartDataPointCollection::AddDataPointForBarSeries(double) metoda

Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž chartType je jeden z [Column](../../../aspose.slides/column/) nebo podtypy Bar (viz také [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) a [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metoda).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota datového bodu |

### Návratová hodnota

Nový datový bod.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataPoint](../../ichartdatapoint/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [ChartDataPointCollection](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)