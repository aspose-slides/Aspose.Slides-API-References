---
title: Axis
second_title: Aspose.Slides for Java API 参考
description: 封装代表图表轴的对象。
type: docs
url: /zh/com.aspose.slides/axis/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

封装表示图表轴的对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getChart()](#getChart--) | 返回父 chart。 |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 表示值轴是否在类别轴之间交叉。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 表示值轴是否在类别轴之间交叉。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | 指定类别轴的类型。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 指定类别轴的类型。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 使用基于轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。 |
| [getCrossAt()](#getCrossAt--) | 表示垂直轴在轴上交叉的点。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 表示垂直轴在轴上交叉的点。 |
| [getDisplayUnit()](#getDisplayUnit--) | 指定值轴显示单位的缩放值。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 指定值轴显示单位的缩放值。 |
| [getActualMaxValue()](#getActualMaxValue--) | 指定轴上的实际最大值。 |
| [getActualMinValue()](#getActualMinValue--) | 指定轴上的实际最小值。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 指定轴的实际主单位。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 指定轴的实际次单位。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 指定轴的实际主单位比例。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 指定轴的实际次单位比例。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 指示最大值是否自动分配。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 指示最大值是否自动分配。 |
| [getMaxValue()](#getMaxValue--) | 表示值轴的最大值。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 表示值轴的最大值。 |
| [getMinorUnit()](#getMinorUnit--) | 表示日期或值轴的次单位。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 表示日期或值轴的次单位。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 指示轴的次单位是否自动分配。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 指示轴的次单位是否自动分配。 |
| [getMajorUnit()](#getMajorUnit--) | 表示日期或值轴的主单位。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 表示日期或值轴的主单位。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 指示轴的主单位是否自动分配。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 指示轴的主单位是否自动分配。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 指示最小值是否自动分配。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 指示最小值是否自动分配。 |
| [getMinValue()](#getMinValue--) | 表示值轴的最小值。 |
| [setMinValue(double value)](#setMinValue-double-) | 表示值轴的最小值。 |
| [isLogarithmic()](#isLogarithmic--) | 表示值轴的刻度类型是否为对数。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 表示值轴的刻度类型是否为对数。 |
| [getLogBase()](#getLogBase--) | 表示对数基数。 |
| [setLogBase(double value)](#setLogBase-double-) | 表示对数基数。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。 |
| [isVisible()](#isVisible--) | 表示轴是否可见。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 表示轴是否可见。 |
| [getMajorTickMark()](#getMajorTickMark--) | 表示指定轴的主刻度标记类型。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 表示指定轴的主刻度标记类型。 |
| [getMinorTickMark()](#getMinorTickMark--) | 表示指定轴的次刻度标记类型。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 表示指定轴的次刻度标记类型。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 表示指定轴上刻度标签的位置。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 表示指定轴上刻度标签的位置。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 表示日期轴的主单位比例。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 表示日期轴的主单位比例。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 表示日期轴的主单位比例。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 表示日期轴的主单位比例。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 指定日期轴上表示的最小时间单位。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 指定日期轴上表示的最小时间单位。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 表示图表轴上次网格线的格式。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 表示图表轴上主网格线的格式。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 要隐藏次网格线，请将 MinorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 要隐藏主网格线，请将 MajorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。 |
| [getFormat()](#getFormat--) | 表示轴的格式。 |
| [getTextFormat()](#getTextFormat--) | 表示文本的格式。 |
| [getTitle()](#getTitle--) | 获取轴的标题。 |
| [getCrossType()](#getCrossType--) | 表示指定轴上另一轴交叉的 CrossType。 |
| [setCrossType(int value)](#setCrossType-int-) | 表示指定轴上另一轴交叉的 CrossType。 |
| [getPosition()](#getPosition--) | 表示轴的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示轴的位置。 |
| [hasTitle()](#hasTitle--) | 确定轴是否具有可见标题。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 确定轴是否具有可见标题。 |
| [getNumberFormat()](#getNumberFormat--) | 表示轴标签的格式字符串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示轴标签的格式字符串。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 指示格式是否链接到源数据。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 指示格式是否链接到源数据。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 表示刻度标签的旋转角度。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 表示刻度标签的旋转角度。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 指定在绘制的标签之间跳过的刻度标签数量。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 指定在绘制的标签之间跳过的刻度标签数量。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 指定自动刻度标签间距值。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 指定自动刻度标签间距值。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 指定在绘制下一个刻度之前应跳过的刻度线数量。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 指定在绘制下一个刻度之前应跳过的刻度线数量。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 指定自动刻度线间距值。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 指定自动刻度线间距值。 |
| [getLabelOffset()](#getLabelOffset--) | 指定标签离轴的距离。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 指定标签离轴的距离。 |
| [getAggregationType()](#getAggregationType--) | 表示类别轴（分箱）的聚合类型。 |
| [setAggregationType(int value)](#setAggregationType-int-) | 表示类别轴（分箱）的聚合类型。 |
| [getBinWidth()](#getBinWidth--) | 当 AggregationType 属性值设为 AxisAggregationType.ByBinWidth 时，指定分箱宽度。 |
| [setBinWidth(double value)](#setBinWidth-double-) | 当 AggregationType 属性值设为 AxisAggregationType.ByBinWidth 时，指定分箱宽度。 |
| [getNumberOfBins()](#getNumberOfBins--) | 当 AggregationType 属性值设为 AxisAggregationType.ByNumberOfBins 时，指定分箱数量。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | 当 AggregationType 属性值设为 AxisAggregationType.ByNumberOfBins 时，指定分箱数量。 |
| [isOverflowBin()](#isOverflowBin--) | 指示是否应用溢出分箱。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 指示是否应用溢出分箱。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 指定自动溢出分箱值。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 指定自动溢出分箱值。 |
| [getOverflowBin()](#getOverflowBin--) | 指定溢出分箱的自定义值。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 指定溢出分箱的自定义值。 |
| [isUnderflowBin()](#isUnderflowBin--) | 指示是否应用欠缺分箱。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 指示是否应用欠缺分箱。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 指定自动欠缺分箱值。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 指定自动欠缺分箱值。 |
| [getUnderflowBin()](#getUnderflowBin--) | 指定欠缺分箱的自定义值。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 指定欠缺分箱的自定义值。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父 chart。只读 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

表示值轴是否在类别轴之间交叉。此属性仅适用于类别轴，在 3-D 图表中不适用。读/写 boolean。

**返回：**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

表示值轴是否在类别轴之间交叉。此属性仅适用于类别轴，在 3-D 图表中不适用。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

指定类别轴的类型。读/写 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)。

**返回：**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

指定类别轴的类型。读/写 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

使用基于轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

表示垂直轴在轴上交叉的点。读/写 float。

**返回：**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

表示垂直轴在轴上交叉的点。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

指定值轴显示单位的缩放值。读/写 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**返回：**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

指定值轴显示单位的缩放值。读/写 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

指定轴上的实际最大值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

指定轴上的实际最小值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

指定轴的实际主单位。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

指定轴的实际次单位。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

指定轴的实际主单位比例。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

指定轴的实际次单位比例。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。

**返回：**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

指示最大值是否自动分配。读/写 boolean。

**返回：**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

指示最大值是否自动分配。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

表示值轴的最大值。读/写 double。

**返回：**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

表示值轴的最大值。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

表示日期或值轴的次单位。读/写 double。

**返回：**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

表示日期或值轴的次单位。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
指示轴的次要单位是否自动分配。读/写 boolean.

**返回：**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


指示轴的次要单位是否自动分配。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


表示日期或数值轴的主要单位。读/写 double。

**返回：**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


表示日期或数值轴的主要单位。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


指示轴的主要单位是否自动分配。读/写 boolean。

**返回：**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


指示轴的主要单位是否自动分配。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


指示最小值是否自动分配。读/写 boolean。

**返回：**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


指示最小值是否自动分配。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


表示数值轴的最小值。读/写 double。

**返回：**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


表示数值轴的最小值。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


表示数值轴的比例类型是否为对数。读/写 boolean。

**返回：**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


表示数值轴的比例类型是否为对数。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


表示对数基数。默认值为 10。读/写 double。

**返回：**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


表示对数基数。默认值为 10。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


表示 Microsoft PowerPoint 是否从最后到第一绘制数据点。读/写 boolean。

**返回：**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


表示 Microsoft PowerPoint 是否从最后到第一绘制数据点。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


表示轴是否可见。读/写 boolean。

**返回：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


表示轴是否可见。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


表示指定轴的主要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**返回：**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


表示指定轴的主要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


表示指定轴的次要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**返回：**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


表示指定轴的次要刻度标记类型。读/写 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


表示指定轴上刻度标签的位置。读/写 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**返回：**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


表示指定轴上刻度标签的位置。读/写 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


表示日期轴的主要单位比例。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


指定日期轴上表示的最小时间单位。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


指定日期轴上表示的最小时间单位。读/写 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


表示图表轴的次要网格线格式。只读 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**返回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


表示图表轴的主要网格线格式。只读 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**返回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


要隐藏次要网格线，请将 MinorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。只读 boolean。

**返回：**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


要隐藏主要网格线，请将 MajorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。只读 boolean。

**返回：**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


表示轴的格式。只读 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**返回：**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


表示文本的格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


获取轴的标题。只读 [IChartTitle](../../com.aspose.slides/icharttitle)。

**返回：**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


表示指定轴上另一轴交叉的 CrossType。读/写 [CrossesType](../../com.aspose.slides/crossestype)。

**返回：**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


表示指定轴上另一轴交叉的 CrossType。读/写 [CrossesType](../../com.aspose.slides/crossestype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


表示轴的位置。读/写 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**返回：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


表示轴的位置。读/写 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


确定轴是否具有可见标题。读/写 boolean。

**返回：**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


确定轴是否具有可见标题。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


表示轴标签的格式字符串。读/写 String。

**返回：**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


表示轴标签的格式字符串。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


指示格式是否链接到源数据。读/写 boolean。

**返回：**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


指示格式是否链接到源数据。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


表示刻度标签的旋转角度。读/写 float。

**返回：**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


表示刻度标签的旋转角度。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


指定在绘制的标签之间要跳过的刻度标签数。适用于类别轴或系列轴。读/写 long。

**返回：**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


指定在绘制的标签之间要跳过的刻度标签数。适用于类别轴或系列轴。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


指定自动刻度标签间距值。若为 false：使用 TickLabelSpacing 属性。读/写 boolean。

**返回：**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


指定自动刻度标签间距值。若为 false：使用 TickLabelSpacing 属性。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


指定在绘制下一个刻度标记之前要跳过的刻度标记数。适用于类别轴或系列轴。读/写 int。

**返回：**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


指定在绘制下一个刻度标记之前要跳过的刻度标记数。适用于类别轴或系列轴。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


指定自动刻度标记间距值。若为 false：使用 TickMarksSpacing 属性。读/写 boolean。

**返回：**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


指定自动刻度标记间距值。若为 false：使用 TickMarksSpacing 属性。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


指定标签与轴的距离。适用于类别轴或日期轴。值必须在 0% 到 1000% 之间。读/写 int。

**返回：**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


指定标签与轴的距离。适用于类别轴或日期轴。值必须在 0% 到 1000% 之间。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

表示分类轴的聚合类型（分箱）。适用于类别。仅在 Histogram 或 HistogramPareto 系列中使用。

**Returns:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

表示分类轴的聚合类型（分箱）。适用于类别。仅在 Histogram 或 HistogramPareto 系列中使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定分箱宽度。适用于分类坐标轴。仅在 Histogram 或 HistogramPareto 系列中使用。

**Returns:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定分箱宽度。适用于分类坐标轴。仅在 Histogram 或 HistogramPareto 系列中使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定分箱数量。适用于分类坐标轴。仅在 Histogram 或 HistogramPareto 系列中使用。

**Returns:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时指定分箱数量。适用于分类坐标轴。仅在 Histogram 或 HistogramPareto 系列中使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱的值。

**Returns:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

指定自动溢出分箱的值。如果为 false：使用 OverflowBin 属性。

**Returns:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

指定自动溢出分箱的值。如果为 false：使用 OverflowBin 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性为 true 时应用。

**Returns:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性为 true 时应用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢分箱的值。

**Returns:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢分箱的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

指定自动下溢分箱的值。如果为 false：使用 UnderflowBin 属性。

**Returns:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

指定自动下溢分箱的值。如果为 false：使用 UnderflowBin 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性为 true 时应用。

**Returns:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性为 true 时应用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)