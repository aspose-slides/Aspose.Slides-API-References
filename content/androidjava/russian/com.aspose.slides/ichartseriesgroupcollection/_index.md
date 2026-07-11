---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides для Android через Java API Reference
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

1) Каждая группа рядов содержит ряды с комбинируемыми типами. Группы комбинируемых типов рядов определены и описаны перечислением CombinableSeriesTypesGroup. Кроме того, каждая группа рядов содержит ряды, которые отображаются либо на основных осях, либо на вторичных осях (не оба случая в одной группе). Таким образом, принцип группировки рядов — это группировка по типам групп, упомянутым выше, и по типу отображения — основной/вторичный. 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе («свойства группы рядов»). «Свойства группы рядов» в классе ChartSeriesGroup доступны для чтения и записи. Каждое из «свойств группы рядов» может иметь только-чтение проекцию в классе ChartSeries.
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