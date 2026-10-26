---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides для Android через справку по Java API
description: Представляет коллекцию точек для разделения в диаграмме типа bar-of-pie или pie-of-pie с пользовательским разбиением.
type: docs
url: /ru/com.aspose.slides/piesplitcustompointcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Представляет коллекцию точек для разделения в диаграмме типа bar-of-pie или pie-of-pie с пользовательским разбиением.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает точку данных диаграммы для указанного индекса. |
| [add(int dataPointIndex)](#add-int-) | Добавляет точку данных по её индексу в коллекции точек серии-родителя. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Добавляет точку данных в коллекцию. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Удаляет элемент из коллекции. |
| [remove(int dataPointIndex)](#remove-int-) | Удаляет элемент из коллекции по его индексу в коллекции точек серии-родителя. |
| [clear()](#clear--) | Удаляет все элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с указанного индекса массива. |
| [size()](#size--) | Возвращает или задаёт количество точек данных диаграммы. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает синхронизационный корень. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Возвращает точку данных диаграммы для указанного индекса.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |

**Возвращает:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Точка данных диаграммы.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Добавляет точку данных по её индексу в коллекции точек серии-родителя.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | int | Индекс точки данных в коллекции точек серии-родителя. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Добавляет точку данных в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Точка данных, которую добавить. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Удаляет элемент из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Точка данных, которую удалить. |

**Возвращает:**
boolean — true, если элемент успешно удалён; иначе false. Этот метод также возвращает false, если элемент не найден в System.Collections.Generic.List{T}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Удаляет элемент из коллекции по его индексу в коллекции точек серии-родителя.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | int | Индекс точки данных в коллекции точек серии-родителя. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Объект для поиска в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean - true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с указанного индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Одномерный массив, в который копируются элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен быть с нулевой базой индексов. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### size() {#size--}
```
public final int size()
```

Возвращает или задаёт количество точек данных диаграммы. Только для чтения int.

**Возвращает:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Только для чтения boolean.

**Возвращает:**
boolean - true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает синхронизационный корень. Только для чтения Object.

**Возвращает:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator для всей коллекции.