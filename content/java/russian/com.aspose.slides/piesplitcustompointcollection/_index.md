---
title: PieSplitCustomPointCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию точек для разбиения в диаграмме «бар-круг» или «круг-круг» с пользовательским разбиением.
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

Представляет коллекцию точек для разбиения в диаграмме «бар-круг» или «круг-круг» с пользовательским разбиением.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает точку данных диаграммы для указанного индекса. |
| [add(int dataPointIndex)](#add-int-) | Добавляет точку данных по её индексу в коллекции точек родительского ряда. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Добавляет точку данных в коллекцию. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Удаляет элемент из коллекции. |
| [remove(int dataPointIndex)](#remove-int-) | Удаляет элемент из коллекции по его индексу в коллекции точек родительского ряда. |
| [clear()](#clear--) | Удаляет все элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива. |
| [size()](#size--) | Возвращает или задаёт количество точек данных диаграммы. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
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

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Точка данных диаграммы.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Добавляет точку данных по её индексу в коллекции точек родительского ряда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | int | Индекс точки данных в коллекции точек родительского ряда. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Добавляет точку данных в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Точка данных для добавления. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Удаляет элемент из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Точка данных для удаления. |

**Возвращаемое значение:**
boolean – true, если элемент успешно удалён; иначе false. Этот метод также возвращает false, если элемент не найден в System.Collections.Generic.List\{T\}.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Удаляет элемент из коллекции по его индексу в коллекции точек родительского ряда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | int | Индекс точки данных в коллекции точек родительского ряда. |

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
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Объект, который нужно найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean – true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Одномерный массив, который является получателем элементов, скопированных из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен иметь нулевую базу индекса. |
| arrayIndex | int | Нулевой базовый индекс в массиве, с которого начинается копирование. |

### size() {#size--}
```
public final int size()
```

Возвращает или задаёт количество точек данных диаграммы. Толькo для чтения int.

**Возвращаемое значение:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Толькo для чтения boolean.

**Возвращаемое значение:**
boolean – true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Толькo для чтения boolean.

**Возвращаемое значение:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. Толькo для чтения Object.

**Возвращаемое значение:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> – IGenericEnumerator, который можно использовать для итерации по коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> – java.util.Iterator для всей коллекции.