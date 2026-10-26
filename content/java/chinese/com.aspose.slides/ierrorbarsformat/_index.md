---
title: IErrorBarsFormat
second_title: Aspose.Slides for Java API 参考
description: 表示图表系列的误差线。
type: docs
url: /zh/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

表示图表系列的误差线。ErrorBars 的自定义值位于 IChartDataPointCollection 中（在 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 属性中）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取或设置误差线的类型。 |
| [setType(int value)](#setType-int-) | 获取或设置误差线的类型。 |
| [getValueType()](#getValueType--) | 表示确定误差线长度的可能方式。 |
| [setValueType(int value)](#setValueType-int-) | 表示确定误差线长度的可能方式。 |
| [hasEndCap()](#hasEndCap--) | 指定误差线不绘制端帽。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 指定误差线不绘制端帽。 |
| [getValue()](#getValue--) | 获取或设置用于在 Fixed、Percentage 和 StandardDeviation 值类型下确定误差线长度的值。 |
| [setValue(float value)](#setValue-float-) | 获取或设置用于在 Fixed、Percentage 和 StandardDeviation 值类型下确定误差线长度的值。 |
| [getFormat()](#getFormat--) | 表示误差线的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示误差线的格式。 |
| [isVisible()](#isVisible--) | 获取或设置误差线的可见性。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置误差线的可见性。 |
### getType() {#getType--}
```
public abstract int getType()
```

获取或设置误差线的类型。读/写 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**返回：**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

获取或设置误差线的类型。读/写 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

表示确定误差线长度的可能方式。对于自定义值类型，请使用系列 DataPoints 集合中特定数据点的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 属性。读/写 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**返回：**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

表示确定误差线长度的可能方式。对于自定义值类型，请使用系列 DataPoints 集合中特定数据点的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 属性。读/写 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

指定误差线不绘制端帽。读/写 boolean。

**返回：**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

指定误差线不绘制端帽。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

获取或设置用于在 Fixed、Percentage 和 StandardDeviation 值类型下确定误差线长度的值。读/写 float。

**返回：**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

获取或设置用于在 Fixed、Percentage 和 StandardDeviation 值类型下确定误差线长度的值。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示误差线的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示误差线的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

获取或设置误差线的可见性。读/写 boolean。

**返回：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

获取或设置误差线的可见性。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |