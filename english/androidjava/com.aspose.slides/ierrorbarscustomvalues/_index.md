---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the errors bar values.
type: docs
weight: 765
url: /androidjava/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Specifies the errors bar values. It shall be used only when the Error bars value type is Custom.
## Methods

| Method | Description |
| --- | --- |
| [getXMinus()](#getXMinus--) | Specifies the error bar value in the negative direction. |
| [getYMinus()](#getYMinus--) | Specifies the error bar value in the negative direction. |
| [getXPlus()](#getXPlus--) | Specifies the error bar value in the positive direction. |
| [getYPlus()](#getYPlus--) | Specifies the error bar value in the positive direction. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


Specifies the error bar value in the negative direction. Available if error bars value type is Custom and ErrorBarsXFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


Specifies the error bar value in the negative direction. Available if error bars value type is Custom and ErrorBarsYFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


Specifies the error bar value in the positive direction. Available if error bars value type is Custom and ErrorBarsXFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


Specifies the error bar value in the positive direction. Available if error bars value type is Custom and ErrorBarsYFormat is allowed. In any other case this property returns null. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
