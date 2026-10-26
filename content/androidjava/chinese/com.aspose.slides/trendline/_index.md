---
title: Trendline
second_title: Aspose.Slides for Android via Java API 参考
description: 类表示图表系列的趋势线
type: docs
url: /zh/com.aspose.slides/trendline/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

类表示图表系列的趋势线
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | 获取或设置 trendline 的名称。 |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | 获取或设置 trendline 的名称。 |
| [getTrendlineType()](#getTrendlineType--) | 获取或设置 trendline 的类型。 |
| [setTrendlineType(int value)](#setTrendlineType-int-) | 获取或设置 trendline 的类型。 |
| [getFormat()](#getFormat--) | 表示 trendline 的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示 trendline 的格式。 |
| [getBackward()](#getBackward--) | 指定 trendline 在系列数据之前向前延伸的类别（或散点图上的单位）数量。 |
| [setBackward(double value)](#setBackward-double-) | 指定 trendline 在系列数据之前向前延伸的类别（或散点图上的单位）数量。 |
| [getForward()](#getForward--) | 指定 trendline 在系列数据之后向后延伸的类别（或散点图上的单位）数量。 |
| [setForward(double value)](#setForward-double-) | 指定 trendline 在系列数据之后向后延伸的类别（或散点图上的单位）数量。 |
| [getIntercept()](#getIntercept--) | 指定 trendline 与 y 轴交叉的值。 |
| [setIntercept(double value)](#setIntercept-double-) | 指定 trendline 与 y 轴交叉的值。 |
| [getDisplayEquation()](#getDisplayEquation--) | 指定在图表上显示 trendline 的方程（与 Rsquaredvalue 同标签）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 指定在图表上显示 trendline 的方程（与 Rsquaredvalue 同标签）。 |
| [getOrder()](#getOrder--) | 指定多项式 trendline 的阶数。 |
| [setOrder(byte value)](#setOrder-byte-) | 指定多项式 trendline 的阶数。 |
| [getPeriod()](#getPeriod--) | 为移动平均趋势线指定趋势线的周期。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 为移动平均趋势线指定趋势线的周期。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 指定在图表上显示 trendline 的 R 平方值（与方程同标签）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 指定在图表上显示 trendline 的 R 平方值（与方程同标签）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示与此 trendline 相关的图例条目，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
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

获取或设置 trendline 的名称。读/写 String。

**返回：**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

获取或设置 trendline 的名称。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

获取或设置 trendline 的类型。读/写 [TrendlineType](../../com.aspose.slides/trendlinetype)。

**返回：**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

获取或设置 trendline 的类型。读/写 [TrendlineType](../../com.aspose.slides/trendlinetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示 trendline 的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示 trendline 的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

指定 trendline 在系列数据之前向前延伸的类别（或散点图上的单位）数量。对散点图和非散点图，值必须为非负数。读/写 double。

**返回：**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

指定 trendline 在系列数据之前向前延伸的类别（或散点图上的单位）数量。对散点图和非散点图，值必须为非负数。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

指定 trendline 在系列数据之后向后延伸的类别（或散点图上的单位）数量。对散点图和非散点图，值必须为非负数。读/写 double。

**返回：**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

指定 trendline 在系列数据之后向后延伸的类别（或散点图上的单位）数量。对散点图和非散点图，值必须为非负数。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

指定 trendline 与 y 轴交叉的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读/写 double。

**返回：**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

指定 trendline 与 y 轴交叉的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

指定在图表上显示 trendline 的方程（与 Rsquaredvalue 同标签）。读/写 boolean。

**返回：**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

指定在图表上显示 trendline 的方程（与 Rsquaredvalue 同标签）。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

指定多项式 trendline 的阶数。对其他趋势线类型忽略。值必须在 2 到 6 之间。读/写 byte。

**返回：**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

指定多项式 trendline 的阶数。对其他趋势线类型忽略。值必须在 2 到 6 之间。读/写 byte。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

为移动平均趋势线指定趋势线的周期。对其他趋势线变体忽略。值必须在 2 到 255 之间。读/写 byte。

**返回：**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

为移动平均趋势线指定趋势线的周期。对其他趋势线变体忽略。值必须在 2 到 255 之间。读/写 byte。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

指定在图表上显示 trendline 的 R 平方值（与方程同标签）。读/写 boolean。

**返回：**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

指定在图表上显示 trendline 的 R 平方值（与方程同标签）。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

表示与此 trendline 相关的图例条目，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

使用参数 "text" 中的文本初始化 TextFrameForOverriding。若 TextFrameForOverriding 已经初始化，则仅更改其文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文本。 |

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

可以包含富格式文本。若此属性不为 null，则该格式化文本会覆盖数据标签的自动生成文本。自动生成的文本是由 ShowSeriesName、ShowValue 等属性管理，并使用 TextFormatManager.TextFormat 属性进行格式化。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)