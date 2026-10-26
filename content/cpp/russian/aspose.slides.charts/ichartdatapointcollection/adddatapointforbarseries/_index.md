---
title: AddDataPointForBarSeries()
second_title: Справочник API Aspose.Slides для C++
description: Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, тип диаграммы которых является одним из подтипов Column или Bar (см. также ChartTypeCharacterizer.IsChartTypeColumn(ChartType) и ChartTypeCharacterizer.IsChartTypeBar(ChartType) метод).
type: docs
weight: 196
url: /ru/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) метод

Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для серий, тип диаграммы которых является одним из [Column](../../../aspose.slides/column/) или подтипов Bar (см. также [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) и [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных |

### Возвращаемое значение

Новая точка данных.

## IChartDataPointCollection::AddDataPointForBarSeries(double) метод

Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для серий, тип диаграммы которых является одним из [Column](../../../aspose.slides/column/) или подтипов Bar (см. также [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) и [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
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
* Класс [IChartDataPointCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)