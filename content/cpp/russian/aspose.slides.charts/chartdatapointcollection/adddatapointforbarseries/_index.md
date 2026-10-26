---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides для C++ справочник API
description: "Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Column или Bar (см. также ChartTypeCharacterizer::IsChartTypeColumn(ChartType) и ChartTypeCharacterizer::IsChartTypeBar(ChartType) метод)."
type: docs
weight: 261
url: /ru/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из [Column](../../../aspose.slides/column/) или подтипов Bar (см. также метод [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) и [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных |

### Возвращаемое значение

Новая точка данных.

## ChartDataPointCollection::AddDataPointForBarSeries(double) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из [Column](../../../aspose.slides/column/) или подтипов Bar (см. также метод [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) и [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение точки данных |

### Возвращаемое значение

Новая точка данных.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataPoint](../../ichartdatapoint/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [ChartDataPointCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)