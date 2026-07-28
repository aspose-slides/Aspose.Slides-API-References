---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides dla dokumentacji API C++
description: "Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których chartType jest jednym z podtypów Column lub Bar (zobacz także ChartTypeCharacterizer::IsChartTypeColumn(ChartType) oraz ChartTypeCharacterizer::IsChartTypeBar(ChartType) metodę)."
type: docs
weight: 261
url: /pl/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metoda


Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których chartType jest jednym z [Column](../../../aspose.slides/column/) lub podtypów Bar (zobacz także [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) i [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodę).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wartość punktu danych |

### Wartość zwracana

Nowy punkt danych.

## ChartDataPointCollection::AddDataPointForBarSeries(double) metoda


Tworzy nowy punkt danych i dodaje go na koniec kolekcji. Dotyczy serii, których chartType jest jednym z [Column](../../../aspose.slides/column/) lub podtypów Bar (zobacz także [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) i [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metodę).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
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
* Klasa [ChartDataPointCollection](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)