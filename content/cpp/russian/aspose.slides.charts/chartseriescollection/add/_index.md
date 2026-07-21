---
title: Add()
second_title: Aspose.Slides для C++ Справочник API
description: Создает новую серию диаграммы и добавляет её в коллекцию.
type: docs
weight: 53
url: /ru/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) метод

Создает новую серию диаграммы и добавляет её в коллекцию.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Тип серии |

### Return Value

Новая серия диаграммы.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) метод

Создает новую серию диаграммы из [ChartDataCell](../../chartdatacell/) и добавляет её в коллекцию.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) которые содержат имя серии. |
| type | [ChartType](../../charttype/) | Тип задает тип серии |

### Return Value

Добавленная серия диаграммы или серия, уже находящаяся в коллекции.

## Примечания

Если серия диаграммы получена из той же ячейки, уже присутствующей в коллекции, то метод ничего не добавляет и возвращает её индекс.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) метод

Создает новую серию диаграммы из [ChartCellCollection](../../chartcellcollection/) и добавляет её в коллекцию.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Ячейки, которые содержат имя серии. |
| type | [ChartType](../../charttype/) | Тип задает тип серии |

### Return Value

Добавленная серия диаграммы или серия, уже находящаяся в коллекции.

## Примечания

Если серия диаграммы получена из той же ячейки, уже присутствующей в коллекции, то метод ничего не добавляет и возвращает её индекс.

## ChartSeriesCollection::Add(System::String, ChartType) метод

Создает новую серию диаграммы из значения и добавляет её в коллекцию.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Имя серии. |
| type | [ChartType](../../charttype/) | Тип задает тип серии |

### Return Value

Добавленная серия диаграммы.

## См. также

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartSeries](../../ichartseries/)
* Класс [ChartSeriesCollection](../)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [IChartCellCollection](../../ichartcellcollection/)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)