---
title: TrendlineCollection
second_title: Aspose.Slides для Android через справку Java API
description: Представляет собой коллекцию Trendline
type: docs
url: /ru/com.aspose.slides/trendlinecollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Представляет собой коллекцию Trendline
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [add(int trendlineType)](#add-int-) | Добавляет новый Trendline в конец коллекции и возвращает его. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Удаляет указанное значение. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [Trendline](../../com.aspose.slides/trendline).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Добавляет новый Trendline в конец коллекции и возвращает его.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| trendlineType | int |  |

**Возврат:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возврат:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - IGenericEnumerator, который можно использовать для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возврат:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - java.util.Iterator для всей коллекции.
### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возврат:**
int