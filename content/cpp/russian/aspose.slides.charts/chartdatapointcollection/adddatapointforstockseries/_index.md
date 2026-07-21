---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides для C++ справочника API
description: "Создает новую точку данных и добавляет её в конец коллекции. Применяется для рядов, у которых chartType является одним из подтипов Stock (см. также ChartTypeCharacterizer::IsChartTypeStock(ChartType) метод)."
type: docs
weight: 209
url: /ru/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) метод

Создает новую точку данных и добавляет её в конец коллекции. Применяется для рядов, у которых chartType является одним из подтипов Stock (см. также [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) метод).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## ChartDataPointCollection::AddDataPointForStockSeries(double) метод

Создает новую точку данных и добавляет её в конец коллекции. Применяется для рядов, у которых chartType является одним из подтипов Stock (см. также [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) метод).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataPoint](../../ichartdatapoint/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [ChartDataPointCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)