---
title: DoubleChartValue
second_title: Aspose.Slides for Java API Reference
description: Represent double value which can be stored in pptx presentation document in two ways 1 in cell/cells of workbook related to chart 2 as literal value.
type: docs
weight: 159
url: /com.aspose.slides/doublechartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.
## Methods

| Method | Description |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Returns or sets chart data cell. Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Returns or sets chart data cell. Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Returns or sets value as literal double. Read/write double.

**Returns:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Returns or sets value as literal double. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converts to double.

**Returns:**
double - Returns LiteralDouble if DataSourceType equals DoubleLiterals. If DataSourceType equals Worksheet returns successfully converted to double cell value, otherwise returns NaN.
