---
title: IErrorBarsFormat
second_title: Aspose.Slides for Java API Reference
description: Represents error bars of chart series.
type: docs
weight: 766
url: /com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property).
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets or sets type of error bars. |
| [setType(int value)](#setType-int-) | Gets or sets type of error bars. |
| [getValueType()](#getValueType--) | Represents possible ways to determine the length of the error bars. |
| [setValueType(int value)](#setValueType-int-) | Represents possible ways to determine the length of the error bars. |
| [hasEndCap()](#hasEndCap--) | Specifies an end cap is not drawn on the error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifies an end cap is not drawn on the error bars. |
| [getValue()](#getValue--) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [setValue(float value)](#setValue-float-) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [getFormat()](#getFormat--) | Represents the format of the error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the error bars. |
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility. |
### getType() {#getType--}
```
public abstract int getType()
```


Gets or sets type of error bars. Read/write [ErrorBarType](../../com.aspose.slides/errorbartype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Gets or sets type of error bars. Read/write [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```


Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. Read/write [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Returns:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```


Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. Read/write [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```


Specifies an end cap is not drawn on the error bars. Read/write boolean.

**Returns:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```


Specifies an end cap is not drawn on the error bars. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```


Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. Read/write float.

**Returns:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```


Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Represents the format of the error bars. Read/write [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Represents the format of the error bars. Read/write [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Gets or sets Error Bars visibility. Read/write boolean.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Gets or sets Error Bars visibility. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

