---
title: IChartCellCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of a cells with data.
type: docs
weight: 686
url: /com.aspose.slides/ichartcellcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Represents collection of a cells with data.
## Methods

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Returns address of the set of cells in workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Concatenation string from all cells string values. |
| [get_Item(int index)](#get-Item-int-) | Returns a cell (IChartDataCell) by index. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Add new cell to the collection. |
| [add(Object value)](#add-java.lang.Object-) | Creates [IChartDataCell](../../com.aspose.slides/ichartdatacell) from specified value and adds it to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a cell from the collection by index. |
| [getCount()](#getCount--) | Gets the count of cells in collection. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Returns address of the set of cells in workbook.

**Returns:**
java.lang.String - Address of the set of cells in workbook String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Concatenation string from all cells string values.

**Returns:**
java.lang.String - Resulting string String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Returns a cell (IChartDataCell) by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell with data.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Add new cell to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | New cell to add. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Creates [IChartDataCell](../../com.aspose.slides/ichartdatacell) from specified value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value.

--------------------

This method adds worksheet with name AUTO\_DATA and adds all values there. If you use [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) to add or edit Cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes a cell from the collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell to remove. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the count of cells in collection. Read-only int.

**Returns:**
int
