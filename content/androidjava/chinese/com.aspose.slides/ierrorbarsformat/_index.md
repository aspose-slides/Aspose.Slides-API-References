---
title: IErrorBarsFormat
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示图表系列的误差线。
type: docs
url: /zh/com.aspose.slides/ierrorbarsformat/
---
**所有实现的接口：**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

表示图表系列的误差线。ErrorBars 自定义值位于 IChartDataPointCollection 中（在 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 属性中）。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取或设置误差线的类型。 |
| [setType(int value)](#setType-int-) | 获取或设置误差线的类型。 |
| [getValueType()](#getValueType--) | 表示确定误差线长度的可能方式。 |
| [setValueType(int value)](#setValueType-int-) | 表示确定误差线长度的可能方式。 |
| [hasEndCap()](#hasEndCap--) | 指定不在误差线上绘制端帽。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 指定不在误差线上绘制端帽。 |
| [getValue()](#getValue--) | 获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型的值，以确定误差线的长度。 |
| [setValue(float value)](#setValue-float-) | 获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型的值，以确定误差线的长度。 |
| [getFormat()](#getFormat--) | 表示误差线的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示误差线的格式。 |
| [isVisible()](#isVisible--) | 获取或设置误差线的可见性。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置误差线的可见性。 |
### getType() {#getType--}
```
public abstract int getType()
```


获取或设置误差线的类型。读/写 [ErrorBarType](../../com.aspose.slides/errorbartype).

**返回值：**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


获取或设置误差线的类型。读/写 [ErrorBarType](../../com.aspose.slides/errorbartype).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```


表示确定误差线长度的可能方式。若为自定义值类型，请使用系列 DataPoints 集合中特定数据点的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 属性。读/写 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**返回值：**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```


表示确定误差线长度的可能方式。若为自定义值类型，请使用系列 DataPoints 集合中特定数据点的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 属性。读/写 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```


指定不在误差线上绘制端帽。读/写 boolean.

**返回值：**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```


指定不在误差线上绘制端帽。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```


获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型的值，以确定误差线的长度。读/写 float.

**返回值：**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```


获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型的值，以确定误差线的长度。读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


表示误差线的格式。读/写 [IFormat](../../com.aspose.slides/iformat).

**返回值：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


表示误差线的格式。读/写 [IFormat](../../com.aspose.slides/iformat).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


获取或设置误差线的可见性。读/写 boolean.

**返回值：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


获取或设置误差线的可见性。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |