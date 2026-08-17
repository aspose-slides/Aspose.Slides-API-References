---
title: ErrorBarsFormat
second_title: Aspose.Slides Java API 参考
description: 表示图表系列的误差线。
type: docs
url: /zh/com.aspose.slides/errorbarsformat/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**已实现的接口:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

表示图表系列的误差线。ErrorBars 的自定义值位于 IChartDataPointCollection（在 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 属性中）。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取或设置误差线的类型。 |
| [setType(int value)](#setType-int-) | 获取或设置误差线的类型。 |
| [getValueType()](#getValueType--) | 表示确定误差线长度的可能方式。 |
| [setValueType(int value)](#setValueType-int-) | 表示确定误差线长度的可能方式。 |
| [hasEndCap()](#hasEndCap--) | 指定在误差线上不绘制端帽。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 指定在误差线上不绘制端帽。 |
| [getValue()](#getValue--) | 获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型以确定误差线长度的值。 |
| [setValue(float value)](#setValue-float-) | 获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型以确定误差线长度的值。 |
| [getFormat()](#getFormat--) | 表示误差线的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示误差线的格式。 |
| [getChart()](#getChart--) | 返回父图表。 |
| [isVisible()](#isVisible--) | 获取或设置错误线的可见性。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置错误线的可见性。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |

### getType() {#getType--}
```
public final int getType()
```

获取或设置误差线的类型。读/写 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**返回值:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

获取或设置误差线的类型。读/写 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

表示确定误差线长度的可能方式。对于自定义值类型，请使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 属性来指定系列 DataPoints 集合中特定数据点的值。对于 Fixed、Percentage 或 StandardDeviation 值类型，请使用 Value 属性来指定值。读/写 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**返回值:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

表示确定误差线长度的可能方式。对于自定义值类型，请使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 属性来指定系列 DataPoints 集合中特定数据点的值。对于 Fixed、Percentage 或 StandardDeviation 值类型，请使用 Value 属性来指定值。读/写 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

指定在误差线上不绘制端帽。读/写 boolean。

**返回值:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

指定在误差线上不绘制端帽。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型以确定误差线长度的值。其他情况下将返回 NaN。读/写 float。

**返回值:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型以确定误差线长度的值。其他情况下将返回 NaN。读/写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示误差线的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**返回值:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示误差线的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回值:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

获取或设置错误线的可见性。读/写 boolean。

**返回值:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

获取或设置错误线的可见性。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值:**
[IPresentation](../../com.aspose.slides/ipresentation)