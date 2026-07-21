---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides для C++ справочник API
description: "Создает новую точку данных и добавляет её в конец коллекции. Применимо для рядов, у которых chartType является одним из подтипов Pie (см. также метод ChartTypeCharacterizer::IsChartTypePie(ChartType))."
type: docs
weight: 287
url: /ru/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо для рядов, у которых chartType является одним из подтипов Pie (см. также метод [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### Return Value

New data point.

## ChartDataPointCollection::AddDataPointForPieSeries(double) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо для рядов, у которых chartType является одним из подтипов Pie (см. также метод [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | Data point Value |

### Return Value

New data point.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataPoint](../../ichartdatapoint/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [ChartDataPointCollection](../)
* Пространство имен [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)