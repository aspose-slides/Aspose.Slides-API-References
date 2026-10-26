---
title: ITrendlineCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет собой коллекцию TrendlineEx
type: docs
url: /ru/com.aspose.slides/itrendlinecollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Представляет собой коллекцию TrendlineEx
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [add(int trendlineType)](#add-int-) | Добавляет новый Trendline в конец коллекции и возвращает его. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Удаляет указанное значение. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Получает элемент по указанному индексу. Только для чтения [ITrendline](../../com.aspose.slides/itrendline).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Добавляет новый Trendline в конец коллекции и возвращает его.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| trendlineType | int | Тип Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Возвращаемое значение:**
[ITrendline](../../com.aspose.slides/itrendline) - Новый Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline для удаления [ITrendline](../../com.aspose.slides/itrendline) |