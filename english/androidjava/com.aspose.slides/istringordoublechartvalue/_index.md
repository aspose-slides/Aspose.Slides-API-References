---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represent string or double value which can be stored in pptx presentation document in two ways 1 in cell/cells of workbook related to chart 2 as literal value.
type: docs
weight: 1048
url: /androidjava/com.aspose.slides/istringordoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Represent string or double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.
## Methods

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converts value to double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. Read/write String.

**Returns:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. Read/write double.

**Returns:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converts value to double.

**Returns:**
double - Double value double
