---
title: StringChartValue
second_title: Aspose.Slides for Java API Reference
description: Represent string value which can be stored in pptx presentation document in two ways 1 in cell/cells of workbook related to chart 2 as literal value.
type: docs
weight: 531
url: /com.aspose.slides/stringchartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.
## Methods

| Method | Description |
| --- | --- |
| [getAsCells()](#getAsCells--) | Null value assigning is not allowed. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Null value assigning is not allowed. |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets value as literal string. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets value as literal string. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toString()](#toString--) | Returns string value data. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Sets value from specified cell. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```


Null value assigning is not allowed. Returning value always is not null. Read/write [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Returns:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```


Null value assigning is not allowed. Returning value always is not null. Read/write [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Returns or sets value as literal string. Read/write String.

**Returns:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Returns or sets value as literal string. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```


Returns or sets Data object. Read/write Object.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Returns or sets Data object. Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```


Returns string value data. Return null if DataSourceType is false and no string value was assigned.

**Returns:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```


Sets value from specified cell.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```


If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. Otherwise return empty string.

**Returns:**
java.lang.String
