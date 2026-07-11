---
title: ChartCellCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию ячеек с данными.
type: docs
url: /ru/com.aspose.slides/chartcellcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Представляет коллекцию ячеек с данными.
## Методы

| Метод | Описание |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Возвращает адрес набора ячеек в рабочей книге. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Строка конкатенации всех строковых значений ячеек. |
| [get_Item(int index)](#get-Item-int-) | Возвращает ячейку (IChartDataCell) по индексу. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Добавляет новую ячейку в коллекцию. |
| [add(Object value)](#add-java.lang.Object-) | Создаёт [ChartDataCell](../../com.aspose.slides/chartdatacell) из указанного значения и добавляет его в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет ячейку из коллекции по индексу. |
| [getCount()](#getCount--) | Получает количество ячеек в коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Возвращает адрес набора ячеек в рабочей книге.

**Возвращаемое значение:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Строка конкатенации всех строковых значений ячеек.

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
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Ячейка с данными.
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

Этот метод добавляет лист с именем AUTO_DATA и помещает туда все значения. Если вы используете [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) для добавления или изменения значений ячеек, убедитесь, что вы не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680 |
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


Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator для всей коллекции.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject