---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie do serii, których chartType jest jednym z podtypów Column lub Bar (zobacz także ChartTypeCharacterizer.IsChartTypeColumn(ChartType) oraz ChartTypeCharacterizer.IsChartTypeBar(ChartType) metodę).
type: docs
weight: 196
url: /pl/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metoda

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie do serii, której chartType jest jednym z [Column](../../../aspose.slides/column/) lub podtypów Bar (zobacz również [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) i [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodę).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wartość punktu danych |

### Wartość zwracana

Nowy punkt danych.

## IChartDataPointCollection::AddDataPointForBarSeries(double) metoda

Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Ma zastosowanie do serii, której chartType jest jednym z [Column](../../../aspose.slides/column/) lub podtypów Bar (zobacz również [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) i [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodę).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość punktu danych |

### Wartość zwracana

Nowy punkt danych.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataPoint](../../ichartdatapoint/)
* Klasa [IChartDataCell](../../ichartdatacell/)
* Klasa [IChartDataPointCollection](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)