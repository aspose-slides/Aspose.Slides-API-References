---
title: ErrorBarsCustomValues
second_title: Aspose.Sildes for Java API Reference
description: p
 Specifies the errors bar values.
type: docs
weight: 182
url: /java/com.aspose.slides/errorbarscustomvalues/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

Specifies the errors bar values. It shall be used only when the Error bars value type is Custom.
## Constructors

| Constructor | Description |
| --- | --- |
| [ErrorBarsCustomValues(ChartDataPoint parentImmediate)](#ErrorBarsCustomValues-com.aspose.slides.ChartDataPoint-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getXMinus()](#getXMinus--) | Specifies the error bar value in the negative direction. |
| [getYMinus()](#getYMinus--) | Specifies the error bar value in the negative direction. |
| [getXPlus()](#getXPlus--) | Specifies the error bar value in the positive direction. |
| [getYPlus()](#getYPlus--) | Specifies the error bar value in the positive direction. |
### ErrorBarsCustomValues(ChartDataPoint parentImmediate) {#ErrorBarsCustomValues-com.aspose.slides.ChartDataPoint-}
```
 ErrorBarsCustomValues(ChartDataPoint parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [ChartDataPoint](../../com.aspose.slides/chartdatapoint) |  |

### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```


Specifies the error bar value in the negative direction. Available if error bars value type is Custom and ErrorBarsXFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```


Specifies the error bar value in the negative direction. Available if error bars value type is Custom and ErrorBarsYFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```


Specifies the error bar value in the positive direction. Available if error bars value type is Custom and ErrorBarsXFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```


Specifies the error bar value in the positive direction. Available if error bars value type is Custom and ErrorBarsYFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
