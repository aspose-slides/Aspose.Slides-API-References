---
title: IChartSeriesGroupCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию групп комбинируемых рядов.
type: docs
url: /ru/com.aspose.slides/ichartseriesgroupcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Представляет коллекцию групп комбинируемых рядов.

--------------------

1) Каждая группа рядов содержит ряды с комбинируемыми типами. Группы комбинируемых типов рядов определены и описаны с помощью перечисления CombinableSeriesTypesGroup. Также каждая группа рядов содержит ряд, который отображается либо на основной оси, либо на вторичной оси (не обе ситуации в одной группе). Таким образом, принцип группировки рядов — это группировка по перечисленным выше типовым группам и по типу построения (основная/вторичная ось). 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе ("Series group properties"). "Series group properties" в классе ChartSeriesGroup имеет режим чтения/записи. Каждый из "Series group properties" может иметь только для чтения проекцию в классе ChartSeries.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Получает группу рядов по ряду. |
| [get_Item(int index)](#get-Item-int-) | Получает группу рядов по индексу. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Получает группу рядов по ряду.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Возвращаемое значение:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Получает группу рядов по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)