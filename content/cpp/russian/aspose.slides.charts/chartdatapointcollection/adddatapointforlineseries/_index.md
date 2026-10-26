---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides для C++ API Reference
description: "Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Line (см. также метод ChartTypeCharacterizer::IsChartTypeLine(ChartType))."
type: docs
weight: 222
url: /ru/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Line (см. также [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) метод).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## ChartDataPointCollection::AddDataPointForLineSeries(double) метод

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Line (см. также [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) метод).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataPoint](../../ichartdatapoint/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [ChartDataPointCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)