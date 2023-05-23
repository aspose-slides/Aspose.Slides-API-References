---
title: ChartCellCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of a cells with data.
type: docs
weight: 82
url: /java/com.aspose.slides/chartcellcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Represents collection of a cells with data.
## Methods

| Method | Description |
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


Returns address of the set of cells in workbook.

**Returns:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Concatenation string from all cells string values.

**Returns:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Returns a cell (IChartDataCell) by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell with data.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Add new cell to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | New cell to add. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Creates [ChartDataCell](../../com.aspose.slides/chartdatacell) from specified value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value.

--------------------

This method adds worksheet with name AUTO\_DATA and adds all values there. If you use [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) to add or edit Cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes a cell from the collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell to remove. |

### getCount() {#getCount--}
```
public final int getCount()
```


Gets the count of cells in collection. Read-only int.

**Returns:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - An java.util.Iterator for the entire collection.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
