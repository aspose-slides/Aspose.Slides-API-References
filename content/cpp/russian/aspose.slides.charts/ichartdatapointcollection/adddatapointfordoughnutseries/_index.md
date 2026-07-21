---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides для C++ справочник API
description: Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Doughnut (см. также метод ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method).
type: docs
weight: 235
url: /ru/aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries/
---
## IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Doughnut (см. также [ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных |

### Возвращаемое значение

Новая точка данных.

## IChartDataPointCollection::AddDataPointForDoughnutSeries(double) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Doughnut (см. также [ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(double value)=0
```

### Параметры

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