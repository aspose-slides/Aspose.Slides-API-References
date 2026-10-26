---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides для C++ справки API
description: Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Surface (см. также ChartTypeCharacterizer.IsChartTypeSurface(ChartType) метод).
type: docs
weight: 261
url: /ru/aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries/
---
## IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) метод


Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Surface (см. также [ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных |

### Возвращаемое значение

Новая точка данных.

## IChartDataPointCollection::AddDataPointForSurfaceSeries(double) метод


Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Surface (см. также [ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(double value)=0
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
* Библиотека [Aspose.Slides](../../../)