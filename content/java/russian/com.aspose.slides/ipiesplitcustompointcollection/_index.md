---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides для Java — справочник API
description: Представляет коллекцию точек, которые будут отображаться во второй части круговой или столбчатой диаграммы в комбинированных типах «бар-в-круге» или «круг-в-баре» с пользовательским разбиением.
type: docs
url: /ru/com.aspose.slides/ipiesplitcustompointcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Представляет коллекцию точек, которые будут построены во второй части круговой или столбчатой диаграммы в комбинированных типах «бар-в-круге» или «круг-в-баре» с пользовательским разбиением.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает точку данных диаграммы по индексу. |
| [add(int dataPointIndex)](#add-int-) | Добавляет точку данных по её индексу в коллекции точек родительского ряда. |
| [remove(int dataPointIndex)](#remove-int-) | Удаляет элемент из коллекции по его индексу в коллекции точек родительского ряда. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Возвращает точку данных диаграммы по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Точка данных диаграммы.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Добавляет точку данных по её индексу в коллекции точек родительского ряда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | int | Индекс точки данных в коллекции точек родительского ряда. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Удаляет элемент из коллекции по его индексу в коллекции точек родительского ряда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | int | Индекс точки данных в коллекции точек родительского ряда.. |