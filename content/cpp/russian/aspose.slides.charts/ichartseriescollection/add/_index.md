---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новую серию диаграммы и добавляет её в коллекцию.
type: docs
weight: 14
url: /ru/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) метод

Создаёт новую серию диаграммы и добавляет её в коллекцию.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Тип серии |

### Возвращаемое значение

Новая серия диаграммы.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) метод

Создаёт новую серию диаграммы из [IChartDataCell](../../ichartdatacell/) и добавляет её в коллекцию.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) которые содержат имя серии. |
| type | [ChartType](../../charttype/) | Тип, задающий тип серии |

### Возвращаемое значение

Добавленная серия диаграммы или серия, уже находящаяся в коллекции.

## Замечания

Если серия диаграммы создана из той же ячейки, уже находящейся в коллекции, то метод ничего не добавляет и возвращает её индекс.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) метод

Создаёт новую серию диаграммы из [IChartCellCollection](../../ichartcellcollection/) и добавляет её в коллекцию.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Ячейки, содержащие имя серии. |
| type | [ChartType](../../charttype/) | Тип, задающий тип серии |

### Возвращаемое значение

Добавленная серия диаграммы или серия, уже находящаяся в коллекции.

## Замечания

Если серия диаграммы создана из той же ячейки, уже находящейся в коллекции, то метод ничего не добавляет и возвращает её индекс.



## IChartSeriesCollection::Add(System::String, ChartType) метод

Создаёт новую серию диаграммы из значения и добавляет её в коллекцию.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Имя серии. |
| type | [ChartType](../../charttype/) | Тип, задающий тип серии |

### Возвращаемое значение

Добавленная серия диаграммы.

## См. также

* Перечисление [ChartType](../../charttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IChartSeries](../../ichartseries/)
* Класс [IChartSeriesCollection](../)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [IChartCellCollection](../../ichartcellcollection/)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)