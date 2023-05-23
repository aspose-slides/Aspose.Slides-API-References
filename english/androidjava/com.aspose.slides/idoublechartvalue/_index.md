---
title: IDoubleChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represent double value which can be stored in pptx presentation document in two ways 1 in cell/cells of workbook related to chart 2 as literal value.
type: docs
weight: 749
url: /androidjava/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.
## Methods

| Method | Description |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets literal double value if DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets literal double value if DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converst to double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Returns or sets literal double value if DataSourceType = Charts.DataSourceType.DoubleLiterals. Read/write double.

**Returns:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Returns or sets literal double value if DataSourceType = Charts.DataSourceType.DoubleLiterals. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converst to double.

**Returns:**
double - Double value.
