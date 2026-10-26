---
title: ITrendline
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 类表示图表系列的趋势线
type: docs
url: /zh/com.aspose.slides/itrendline/
---
**已实现的接口:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
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
| [getBackward()](#getBackward--) | 指定趋势线在系列数据之前向前延伸的分类（或散点图上的单位）数量。 |
| [setBackward(double value)](#setBackward-double-) | 指定趋势线在系列数据之前向前延伸的分类（或散点图上的单位）数量。 |
| [getForward()](#getForward--) | 指定趋势线在系列数据之后向后延伸的分类（或散点图上的单位）数量。 |
| [setForward(double value)](#setForward-double-) | 指定趋势线在系列数据之后向后延伸的分类（或散点图上的单位）数量。 |
| [getIntercept()](#getIntercept--) | 指定趋势线与 y 轴交叉的值。 |
| [setIntercept(double value)](#setIntercept-double-) | 指定趋势线与 y 轴交叉的值。 |
| [getDisplayEquation()](#getDisplayEquation--) | 指定在图表上显示趋势线方程（与 Rsquaredvalue 同一标签）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 指定在图表上显示趋势线方程（与 Rsquaredvalue 同一标签）。 |
| [getOrder()](#getOrder--) | 指定多项式趋势线的阶数。 |
| [setOrder(byte value)](#setOrder-byte-) | 指定多项式趋势线的阶数。 |
| [getPeriod()](#getPeriod--) | 指定移动平均趋势线的周期。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 指定移动平均趋势线的周期。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示与此趋势线关联的图例条目，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

获取或设置趋势线的名称。读/写 String。

**返回:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

获取或设置趋势线的名称。读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

获取或设置趋势线的类型。读/写 [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int))。

**返回:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

获取或设置趋势线的类型。读/写 [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int))。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示趋势线的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**返回:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示趋势线的格式。读/写 [IFormat](../../com.aspose.slides/iformat)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

指定趋势线在系列数据之前向前延伸的分类（或散点图上的单位）数量。对于散点图和非散点图，值必须为非负数。读/写 double。

**返回:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

指定趋势线在系列数据之前向前延伸的分类（或散点图上的单位）数量。对于散点图和非散点图，值必须为非负数。读/写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

指定趋势线在系列数据之后向后延伸的分类（或散点图上的单位）数量。对于散点图和非散点图，值必须为非负数。读/写 double。

**返回:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

指定趋势线在系列数据之后向后延伸的分类（或散点图上的单位）数量。对于散点图和非散点图，值必须为非负数。读/写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

指定趋势线与 y 轴交叉的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读/写 double。

**返回:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

指定趋势线与 y 轴交叉的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读/写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

指定在图表上显示趋势线方程（与 Rsquaredvalue 同一标签）。读/写 boolean。

**返回:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

指定在图表上显示趋势线方程（与 Rsquaredvalue 同一标签）。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

指定多项式趋势线的阶数。对其他趋势线类型忽略。值必须在 2 到 6 之间。读/写 byte。

**返回:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

指定多项式趋势线的阶数。对其他趋势线类型忽略。值必须在 2 到 6 之间。读/写 byte。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

指定移动平均趋势线的周期。对其他趋势线变体忽略。值必须在 2 到 255 之间。读/写 byte。

**返回:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

指定移动平均趋势线的周期。对其他趋势线变体忽略。值必须在 2 到 255 之间。读/写 byte。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。读/写 boolean。

**返回:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

指定在图表上显示趋势线的 R-squared 值（与方程同一标签）。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

表示与此趋势线关联的图例条目，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)