---
title: ChartCellCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию ячеек с данными.
type: docs
url: /ru/com.aspose.slides/chartcellcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Represents collection of a cells with data.

## Методы

| Метод | Описание |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Returns address of the set of cells in workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Concatenation string from all cells string values. |
| [get_Item(int index)](#get-Item-int-) | Returns a cell (IChartDataCell) by index. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Add new cell to the collection. |
| [add(Object value)](#add-java.lang.Object-) | Creates [ChartDataCell](../../com.aspose.slides/chartdatacell) from specified value and adds it to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a cell from the collection by index. |
| [getCount()](#getCount--) | Gets the count of cells in collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Возвращает адрес набора ячеек в книге.

**Возвращаемое значение:**
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Конкатенированная строка из всех строковых значений ячеек.

**Возвращаемое значение:**
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Возвращает ячейку (IChartDataCell) по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс ячейки. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell with data.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Добавляет новую ячейку в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Новая ячейка для добавления. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Создаёт [ChartDataCell](../../com.aspose.slides/chartdatacell) из указанного значения и добавляет его в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение.

--------------------

Этот метод добавляет лист с именем AUTO_DATA и добавляет все значения туда. Если вы используете [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) для добавления или изменения значений ячеек, убедитесь, что вы не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет ячейку из коллекции по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс ячейки для удаления. |

### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество ячеек в коллекции. Только для чтения int.

**Возвращаемое значение:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Возвращает итератор java для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator для всей коллекции.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject