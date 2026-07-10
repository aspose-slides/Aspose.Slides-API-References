---
title: IAxis
second_title: Aspose.Slides for Android via Java API 参考
description: 封装表示图表轴的对象。
type: docs
url: /zh/com.aspose.slides/iaxis/
---
**所有实现的接口：**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

封装表示图表轴的对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 表示值轴是否在类别之间跨越分类轴。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 表示值轴是否在类别之间跨越分类轴。 |
| [getCrossAt()](#getCrossAt--) | 表示轴上垂直轴交叉的点。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 表示轴上垂直轴交叉的点。 |
| [getDisplayUnit()](#getDisplayUnit--) | 指定值轴显示单位的缩放值。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 指定值轴显示单位的缩放值。 |
| [getActualMaxValue()](#getActualMaxValue--) | 指定轴上的实际最大值。 |
| [getActualMinValue()](#getActualMinValue--) | 指定轴上的实际最小值。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 指定轴上的实际 major unit。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 指定轴上的实际 minor unit。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 指定轴上的实际 major unit scale。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 指定轴上的实际 minor unit scale。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 指示是否自动分配最大值。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 指示是否自动分配最大值。 |
| [getMaxValue()](#getMaxValue--) | 表示值轴上的最大值。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 表示值轴上的最大值。 |
| [getMinorUnit()](#getMinorUnit--) | 表示日期或值轴的次要单位。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 表示日期或值轴的次要单位。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 指示轴的次要单位是否自动分配。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 指示轴的次要单位是否自动分配。 |
| [getMajorUnit()](#getMajorUnit--) | 表示日期或值轴的主要单位。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 表示日期或值轴的主要单位。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 指示轴的主要单位是否自动分配。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 指示轴的主要单位是否自动分配。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 指示是否自动分配最小值。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 指示是否自动分配最小值。 |
| [getMinValue()](#getMinValue--) | 表示值轴上的最小值。 |
| [setMinValue(double value)](#setMinValue-double-) | 表示值轴上的最小值。 |
| [isLogarithmic()](#isLogarithmic--) | 表示值轴刻度类型是否为对数。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 表示值轴刻度类型是否为对数。 |
| [getLogBase()](#getLogBase--) | 表示对数基数。 |
| [setLogBase(double value)](#setLogBase-double-) | 表示对数基数。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。 |
| [isVisible()](#isVisible--) | 表示轴是否可见。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 表示轴是否可见。 |
| [getMajorTickMark()](#getMajorTickMark--) | 表示指定轴的主要刻度标记类型。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 表示指定轴的主要刻度标记类型。 |
| [getMinorTickMark()](#getMinorTickMark--) | 表示指定轴的次要刻度标记类型。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 表示指定轴的次要刻度标记类型。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 表示指定轴上刻度标签的位置。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 表示指定轴上刻度标签的位置。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 表示日期轴的主要单位比例。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 表示日期轴的主要单位比例。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 表示日期轴的主要单位比例。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 表示日期轴的主要单位比例。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 指定日期轴上表示的最小时间单位。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 指定日期轴上表示的最小时间单位。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 表示图表轴上的次要网格线格式。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 表示图表轴上的主要网格线格式。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 表示是否显示次要网格线。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 表示是否显示主要网格线。 |
| [getFormat()](#getFormat--) | 表示轴的格式。 |
| [getTitle()](#getTitle--) | 获取轴的标题。 |
| [getCrossType()](#getCrossType--) | 表示在指定轴上另一轴交叉的位置的 CrossType。 |
| [setCrossType(int value)](#setCrossType-int-) | 表示在指定轴上另一轴交叉的位置的 CrossType。 |
| [getPosition()](#getPosition--) | 表示轴的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示轴的位置。 |
| [hasTitle()](#hasTitle--) | 确定轴是否具有可见标题。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 确定轴是否具有可见标题。 |
| [getNumberFormat()](#getNumberFormat--) | 表示轴标签的格式字符串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示轴标签的格式字符串。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 指示格式是否链接到源数据。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 指示格式是否链接到源数据。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 表示刻度标签的旋转角度 读/写 float。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 表示刻度标签的旋转角度 读/写 float。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 指定在绘制的标签之间要跳过的刻度标签数量。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 指定在绘制的标签之间要跳过的刻度标签数量。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 指定自动刻度标签间距值。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 指定自动刻度标签间距值。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 指定在绘制下一个刻度标记之前应跳过的刻度标记数量。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 指定在绘制下一个刻度标记之前应跳过的刻度标记数量。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 指定自动刻度标记间距值。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 指定自动刻度标记间距值。 |
| [getLabelOffset()](#getLabelOffset--) | 指定标签距离轴的距离。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 指定标签距离轴的距离。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | 指定分类轴的类型。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 指定分类轴的类型。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 根据轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。 |
| [getAggregationType()](#getAggregationType--) | 表示分类轴的聚合类型（分箱）。 |
| [setAggregationType(int value)](#setAggregationType-int-) | 表示分类轴的聚合类型（分箱）。 |
| [getBinWidth()](#getBinWidth--) | 当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定箱宽。 |
| [setBinWidth(double value)](#setBinWidth-double-) | 当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定箱宽。 |
| [getNumberOfBins()](#getNumberOfBins--) | 当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定箱的数量。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | 当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定箱的数量。 |
| [isOverflowBin()](#isOverflowBin--) | 指定是否应用溢出箱。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 指定是否应用溢出箱。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 指定自动溢出箱值。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 指定自动溢出箱值。 |
| [getOverflowBin()](#getOverflowBin--) | 指定溢出箱的自定义值。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 指定溢出箱的自定义值。 |
| [isUnderflowBin()](#isUnderflowBin--) | 指定是否应用下限箱。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 指定是否应用下限箱。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 指定自动下限箱值。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 指定自动下限箱值。 |
| [getUnderflowBin()](#getUnderflowBin--) | 指定下限箱的自定义值。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 指定下限箱的自定义值。 |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

表示值轴是否在类别之间跨越分类轴。此属性仅适用于分类轴，不适用于 3-D 图表。读/写 boolean。

**返回：**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

表示值轴是否在类别之间跨越分类轴。此属性仅适用于分类轴，不适用于 3-D 图表。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

表示轴上垂直轴交叉的点。读/写 float。

**返回：**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

表示轴上垂直轴交叉的点。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

指定值轴显示单位的缩放值。读/写 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**返回：**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

指定值轴显示单位的缩放值。读/写 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

指定轴上的实际最大值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

指定轴上的实际最小值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

指定轴上的实际 major unit。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

指定轴上的实际 minor unit。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

指定轴上的实际 major unit scale。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

指定轴上的实际 minor unit scale。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

指示是否自动分配最大值。读/写 boolean。

**返回：**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

指示是否自动分配最大值。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

表示值轴上的最大值。读/写 double。

**返回：**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

表示值轴上的最大值。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

表示日期或值轴的次要单位。读/写 double。

**返回：**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

表示日期或值轴的次要单位。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

指示轴的次要单位是否自动分配。读/写 boolean。

**返回：**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

指示轴的次要单位是否自动分配。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

表示日期或值轴的主要单位。读/写 double。

**返回：**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

表示日期或值轴的主要单位。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

指示轴的主要单位是否自动分配。读/写 boolean。

**返回：**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

指示轴的主要单位是否自动分配。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

指示是否自动分配最小值。读/写 boolean。

**返回：**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

指示是否自动分配最小值。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

表示值轴上的最小值。读/写 double。

**返回：**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

表示值轴上的最小值。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

表示值轴的刻度类型是否为对数。读/写 boolean。

**返回：**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

表示值轴的刻度类型是否为对数。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

表示对数基数。默认值为 10。读/写 double。

**返回：**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

表示对数基数。默认值为 10。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

表示 MS PowerPoint 是否从最后到第一个绘制数据点。读/写 boolean。

**返回：**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

表示 MS PowerPoint 是否从最后到第一个绘制数据点。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

表示轴是否可见。读/写 boolean。

**返回：**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

表示轴是否可见。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

表示指定轴的主要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**返回：**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

表示指定轴的主要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

表示指定轴的次要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**返回：**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

表示指定轴的次要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

表示指定轴上刻度标签的位置。读/写 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**返回：**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

表示指定轴上刻度标签的位置。读/写 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

指定日期轴上表示的最小时间单位。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

指定日期轴上表示的最小时间单位。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

表示图表轴上的次要网格线格式。只读 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**返回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

表示图表轴上的主要网格线格式。只读 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**返回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

表示是否显示次要网格线。只读 boolean。

**返回：**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

表示是否显示主要网格线。只读 boolean。

**返回：**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

表示轴的格式。只读 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**返回：**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

获取轴的标题。只读 [IChartTitle](../../com.aspose.slides/icharttitle)。

**返回：**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

表示在指定轴上另一轴交叉的位置的 CrossType。读/写 [CrossesType](../../com.aspose.slides/crossestype)。

**返回：**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

表示在指定轴上另一轴交叉的位置的 CrossType。读/写 [CrossesType](../../com.aspose.slides/crossestype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

表示轴的位置。读/写 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**返回：**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

表示轴的位置。读/写 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

确定轴是否具有可见标题。读/写 boolean。

**返回：**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

确定轴是否具有可见标题。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

表示轴标签的格式字符串。读/写 String。

**返回：**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

表示轴标签的格式字符串。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

指示格式是否链接到源数据。读/写 boolean。

**返回：**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

指示格式是否链接到源数据。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

表示刻度标签的旋转角度 读/写 float。

**返回：**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

表示刻度标签的旋转角度 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

指定在绘制的标签之间要跳过的刻度标签数量。读/写 long。

**返回：**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

指定在绘制的标签之间要跳过的刻度标签数量。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

指定自动刻度标签间距值。若为 false：使用 TickLabelSpacing 属性。读/写 boolean。

**返回：**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

指定自动刻度标签间距值。若为 false：使用 TickLabelSpacing 属性。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

指定在绘制下一个刻度标记之前应跳过的刻度标记数量。适用于分类或系列轴。读/写 int。

**返回：**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

指定在绘制下一个刻度标记之前应跳过的刻度标记数量。适用于分类或系列轴。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

指定自动刻度标记间距值。若为 false：使用 TickMarksSpacing 属性。读/写 boolean。

**返回：**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

指定自动刻度标记间距值。若为 false：使用 TickMarksSpacing 属性。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

指定标签距离轴的距离。适用于分类或日期轴。值必须在 0% 到 1000% 之间。读/写 int。

**返回：**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

指定标签距离轴的距离。适用于分类或日期轴。值必须在 0% 到 1000% 之间。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

指定分类轴的类型。读/写 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**返回：**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

指定分类轴的类型。读/写 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

根据轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

表示分类轴的聚合类型（分箱）。适用于分类。仅在直方图或直方图 Pareto 系列中使用。

**返回：**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

表示分类轴的聚合类型（分箱）。适用于分类。仅在直方图或直方图 Pareto 系列中使用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定箱宽。适用于分类轴。仅在直方图或直方图 Pareto 系列中使用。

**返回：**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定箱宽。适用于分类轴。仅在直方图或直方图 Pareto 系列中使用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定箱的数量。适用于分类轴。仅在直方图或直方图 Pareto 系列中使用。

**返回：**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定箱的数量。适用于分类轴。仅在直方图或直方图 Pareto 系列中使用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

指定是否应用溢出箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出箱值。

**返回：**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

指定是否应用溢出箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出箱值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

指定自动溢出箱值。若为 false：使用 OverflowBin 属性。

**返回：**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

指定自动溢出箱值。若为 false：使用 OverflowBin 属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

指定溢出箱的自定义值。仅在 IsAutomaticOverflowBin 为 false 且 IsOverflowBin 为 true 时适用。

**返回：**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

指定溢出箱的自定义值。仅在 IsAutomaticOverflowBin 为 false 且 IsOverflowBin 为 true 时适用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public  

```

指定是否应用下限箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下限箱值。

**返回：**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

指定是否应用下限箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下限箱值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

指定自动下限箱值。若为 false：使用 UnderflowBin 属性。

**返回：**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

指定自动下限箱值。若为 false：使用 UnderflowBin 属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

指定下限箱的自定义值。仅在 IsAutomaticUnderflowBin 为 false 且 IsUnderflowBin 为 true 时适用。

**返回：**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

指定下限箱的自定义值。仅在 IsAutomaticUnderflowBin 为 false 且 IsUnderflowBin 为 true 时适用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |