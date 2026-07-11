---
title: ChartSeriesCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию
type: docs
url: /ru/com.aspose.slides/chartseriescollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Представляет коллекцию [ChartSeries](../../com.aspose.slides/chartseries)
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [size()](#size--) | Возвращает количество объектов в коллекции. |
| [add(int type)](#add-int-) | Создает новую серию диаграммы и добавляет её в коллекцию. |
| [insert(int index, int type)](#insert-int-int-) | Создает новую серию диаграммы и вставляет её в коллекцию. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Создает новую серию диаграммы из [ChartDataCell](../../com.aspose.slides/chartdatacell) и добавляет её в коллекцию. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Создает новую серию диаграммы из [ChartCellCollection](../../com.aspose.slides/chartcellcollection) и добавляет её в коллекцию. |
| [add(String name, int type)](#add-java.lang.String-int-) | Создает новую серию диаграммы из значения и добавляет её в коллекцию. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Ищет указанный [ChartSeries](../../com.aspose.slides/chartseries) и возвращает нулевой-основанный индекс первого вхождения во весь Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет ActiveX-элемент, хранящийся в указанной позиции, из коллекции. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает итератор Java для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует всю коллекцию в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Элемент по указанному индексу.
### size() {#size--}
```
public final int size()
```

Возвращает количество объектов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Создает новую серию диаграммы и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип серии |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Новая серия диаграммы.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Создает новую серию диаграммы и вставляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Создает новую серию диаграммы из [ChartDataCell](../../com.aspose.slides/chartdatacell) и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ячейка, содержащая имя серии. |
| type | int | Тип серии |

--------------------

Если серия диаграммы, созданная из той же ячейки, уже присутствует в коллекции, метод ничего не добавляет и возвращает её индекс. |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Добавленная серия диаграммы или серия, уже находящаяся в коллекции.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Создает новую серию диаграммы из [ChartCellCollection](../../com.aspose.slides/chartcellcollection) и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Ячейки, содержащие имена серий. |
| type | int | Тип серии |

--------------------

Если серия диаграммы, созданная из тех же ячеек, уже присутствует в коллекции, метод ничего не добавляет и возвращает её индекс. |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Добавленная серия диаграммы или серия, уже находящаяся в коллекции.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Создает новую серию диаграммы из значения и добавляет её в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя серии. |
| type | int | Тип серии |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries) – Добавленная серия диаграммы.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Ищет указанный [ChartSeries](../../com.aspose.slides/chartseries) и возвращает нулевой-основанный индекс первого вхождения во весь Collection

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Значение серии диаграммы. |

**Возвращаемое значение:**
int – Нулевой-основанный индекс первого вхождения значения во весь CollectionBase, если найдено; иначе –1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Значение. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет ActiveX-элемент, хранящийся в указанной позиции, из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента для удаления. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Возвращает итератор Java для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует всю коллекцию в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив |
| index | int | Индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object