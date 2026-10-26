---
title: Trendline
second_title: Aspose.Slides for Java API 参考
description: 类表示图表系列的趋势线
type: docs
url: /zh/com.aspose.slides/trendline/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

类表示图表系列的趋势线  

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | 获取或设置趋势线的名称。 |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | 获取或设置趋势线的名称。 |
| [getTrendlineType()](#getTrendlineType--) | 获取或设置趋势线的类型。 |
| [setTrendlineType(int value)](#setTrendlineType-int-) | 获取或设置趋势线的类型。 |
| [getFormat()](#getFormat--) | 表示趋势线的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示趋势线的格式。 |
| [getBackward()](#getBackward--) | 指定趋势线在被趋势的系列数据之前延伸的类别数（或散点图上的单位）。 |
| [setBackward(double value)](#setBackward-double-) | 指定趋势线在被趋势的系列数据之前延伸的类别数（或散点图上的单位）。 |
| [getForward()](#getForward--) | 指定趋势线在被趋势的系列数据之后延伸的类别数（或散点图上的单位）。 |
| [setForward(double value)](#setForward-double-) | 指定趋势线在被趋势的系列数据之后延伸的类别数（或散点图上的单位）。 |
| [getIntercept()](#getIntercept--) | 指定趋势线应在 y 轴交叉的值。 |
| [setIntercept(double value)](#setIntercept-double-) | 指定趋势线应在 y 轴交叉的值。 |
| [getDisplayEquation()](#getDisplayEquation--) | 指定在图表上显示趋势线的方程（与 Rsquaredvalue 同一标签）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 指定在图表上显示趋势线的方程（与 Rsquaredvalue 同一标签）。 |
| [getOrder()](#getOrder--) | 指定多项式趋势线的阶数。 |
| [setOrder(byte value)](#setOrder-byte-) | 指定多项式趋势线的阶数。 |
| [getPeriod()](#getPeriod--) | 指定移动平均趋势线的周期。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 指定移动平均趋势线的周期。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示与此趋势线相关的图例项，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式文本。 |
| [getTextFormat()](#getTextFormat--) | 返回文本格式。 |
| [getChart()](#getChart--) | 返回父图表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

获取或设置趋势线的名称。读写 String。

**返回值:**  
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

获取或设置趋势线的名称。读写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

获取或设置趋势线的类型。读写 [TrendlineType](../../com.aspose.slides/trendlinetype)。

**返回值:**  
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

获取或设置趋势线的类型。读写 [TrendlineType](../../com.aspose.slides/trendlinetype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示趋势线的格式。读写 [IFormat](../../com.aspose.slides/iformat)。

**返回值:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示趋势线的格式。读写 [IFormat](../../com.aspose.slides/iformat)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

指定趋势线在被趋势的系列数据之前延伸的类别数（或散点图上的单位）。在散点图和非散点图中，该值应为任何非负值。读写 double。

**返回值:**  
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

指定趋势线在被趋势的系列数据之前延伸的类别数（或散点图上的单位）。在散点图和非散点图中，该值应为任何非负值。读写 double。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

指定趋势线在被趋势的系列数据之后延伸的类别数（或散点图上的单位）。在散点图和非散点图中，该值应为任何非负值。读写 double。

**返回值:**  
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

指定趋势线在被趋势的系列数据之后延伸的类别数（或散点图上的单位）。在散点图和非散点图中，该值应为任何非负值。读写 double。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

指定趋势线应在 y 轴交叉的值。仅当趋势线类型为 exp、linear 或 poly 时支持此属性。读写 double。

**返回值:**  
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

指定趋势线应在 y 轴交叉的值。仅当趋势线类型为 exp、linear 或 poly 时支持此属性。读写 double。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

指定在图表上显示趋势线的方程（与 Rsquaredvalue 同一标签）。读写 boolean。

**返回值:**  
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

指定在图表上显示趋势线的方程（与 Rsquaredvalue 同一标签）。读写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

指定多项式趋势线的阶数。对其他趋势线类型忽略此设置。值必须在 2 到 6 之间。读写 byte。

**返回值:**  
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

指定多项式趋势线的阶数。对其他趋势线类型忽略此设置。值必须在 2 到 6 之间。读写 byte。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

指定移动平均趋势线的周期。对其他趋势线变体忽略此设置。值必须在 2 到 255 之间。读写 byte。

**返回值:**  
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

指定移动平均趋势线的周期。对其他趋势线变体忽略此设置。值必须在 2 到 255 之间。读写 byte。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。读写 boolean。

**返回值:**  
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。读写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

表示与此趋势线相关的图例项，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回值:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

使用参数 "text" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 用于新 TextFrameForOverriding 的文本。 |

**返回值:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

可以包含富格式文本。如果此属性不为 null，则此格式化文本值会覆盖数据标签的自动生成文本。自动生成的文本指的是由 ShowSeriesName、ShowValue 等属性管理并使用 TextFormatManager.TextFormat 属性进行格式化的文本。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回值:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回值:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回值:**  
[IChart](../../com.aspose.slides/ichart)

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