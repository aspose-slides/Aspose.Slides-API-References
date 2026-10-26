---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новую точку данных и добавляет её в конец коллекции. Применяется к сериям, у которых chartType является одним из подтипов Stock (см. также ChartTypeCharacterizer.IsChartTypeStock(ChartType) method).
type: docs
weight: 144
url: /ru/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) метод

Создаёт новую точку данных и добавляет её в конец коллекции. Применяется к сериям, у которых chartType является одним из подтипов Stock (см. также [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Значение точки данных. |

### Возвращаемое значение

Новая точка данных.

## IChartDataPointCollection::AddDataPointForStockSeries(double) метод

Создаёт новую точку данных и добавляет её в конец коллекции. Применяется к сериям, у которых chartType является одним из подтипов Stock (см. также [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) метод).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
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
* Класс [IChartDataPointCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)