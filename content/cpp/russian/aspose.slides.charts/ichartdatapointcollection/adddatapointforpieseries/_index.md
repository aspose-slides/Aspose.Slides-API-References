---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для рядов, у которых chartType является одним из подтипов Pie (см. также ChartTypeCharacterizer.IsChartTypePie(ChartType) метод).
type: docs
weight: 222
url: /ru/aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries/
---
## IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) метод

Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для рядов, у которых chartType является одним из подтипов Pie (см. также [ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) method).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных |

### Возвращаемое значение

Новая точка данных.

## IChartDataPointCollection::AddDataPointForPieSeries(double) метод

Создаёт новую точку данных и добавляет её в конец коллекции. Применимо для рядов, у которых chartType является одним из подтипов Pie (см. также [ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) method).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(double value)=0
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