---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides pro rozhraní API C++
description: Vytváří nový datový bod a přidává jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z podtypů Column nebo Bar (viz také ChartTypeCharacterizer.IsChartTypeColumn(ChartType) a ChartTypeCharacterizer.IsChartTypeBar(ChartType) metoda).
type: docs
weight: 196
url: /cs/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metoda

Vytváří nový datový bod a přidává jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z [Column](../../../aspose.slides/column/) nebo podtypů Bar (viz také [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) a [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metoda).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Hodnota datového bodu |

### Návratová hodnota

Nový datový bod.

## IChartDataPointCollection::AddDataPointForBarSeries(double) metoda

Vytváří nový datový bod a přidává jej na konec kolekce. Použitelné pro řady, jejichž chartType je jedním z [Column](../../../aspose.slides/column/) nebo podtypů Bar (viz také [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) a [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metoda).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota datového bodu |

### Návratová hodnota

Nový datový bod.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IChartDataPoint](../../ichartdatapoint/)
* třída [IChartDataCell](../../ichartdatacell/)
* třída [IChartDataPointCollection](../)
* jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)