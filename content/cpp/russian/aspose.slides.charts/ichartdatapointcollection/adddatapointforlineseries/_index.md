---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides для C++ справочник API
description: Создает новую точку данных и добавляет её в конец коллекции. Применяется для серий, у которых chartType является одним из подтипов Line (см. также ChartTypeCharacterizer.IsChartTypeLine(ChartType) метод).
type: docs
weight: 157
url: /ru/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) метод


Создает новую точку данных и добавляет её в конец коллекции. Применяется для серий, у которых chartType является одним из подтипов Line (см. также [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## IChartDataPointCollection::AddDataPointForLineSeries(double) метод


Создает новую точку данных и добавляет её в конец коллекции. Применяется для серий, у которых chartType является одним из подтипов Line (см. также [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)