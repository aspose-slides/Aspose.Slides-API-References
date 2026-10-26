---
title: ChartPlotArea
second_title: Aspose.Slides for Android via Java API 参考
description: 表示绘制图表的矩形区域。
type: docs
url: /zh/com.aspose.slides/chartplotarea/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

表示绘制图表的矩形区域。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 返回绘图区域的格式。 |
| [getX()](#getX--) | 返回或设置绘图区域边界框左上角的 x 坐标，以图表宽度的比例表示（从 0 到 1）。 |
| [setX(float value)](#setX-float-) | 返回或设置绘图区域边界框左上角的 x 坐标，以图表宽度的比例表示（从 0 到 1）。 |
| [getY()](#getY--) | 返回或设置绘图区域边界框左上角的 y 坐标，以图表高度的比例表示（从 0 到 1）。 |
| [setY(float value)](#setY-float-) | 返回或设置绘图区域边界框左上角的 y 坐标，以图表高度的比例表示（从 0 到 1）。 |
| [getWidth()](#getWidth--) | 返回或设置绘图区域边界框的宽度，以图表宽度的比例表示（从 0 到 1）。 |
| [setWidth(float value)](#setWidth-float-) | 返回或设置绘图区域边界框的宽度，以图表宽度的比例表示（从 0 到 1）。 |
| [getHeight()](#getHeight--) | 返回或设置绘图区域边界框的高度，以图表高度的比例表示（从 0 到 1）。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置绘图区域边界框的高度，以图表高度的比例表示（从 0 到 1）。 |
| [getRight()](#getRight--) | 右侧。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getChart()](#getChart--) | 图表。 |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | 定义位置的计算方式：true \\u2013 自动计算；由 X、Y、Width、Height 属性定义。只读 boolean。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | 如果手动定义绘图区域的布局，此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | 如果手动定义绘图区域的布局，此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。 |
| [getActualX()](#getActualX--) | 指定相对于图表左上角的图表元素实际 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定相对于图表左上角的图表元素实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

返回绘图区域的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### getX() {#getX--}
```
public final float getX()
```

返回或设置绘图区域边界框左上角的 x 坐标，以图表宽度的比例表示（从 0 到 1）。读/写 float。

**返回：**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

返回或设置绘图区域边界框左上角的 x 坐标，以图表宽度的比例表示（从 0 到 1）。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

返回或设置绘图区域边界框左上角的 y 坐标，以图表高度的比例表示（从 0 到 1）。读/写 float。

**返回：**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

返回或设置绘图区域边界框左上角的 y 坐标，以图表高度的比例表示（从 0 到 1）。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

返回或设置绘图区域边界框的宽度，以图表宽度的比例表示（从 0 到 1）。读/写 float。

**返回：**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

返回或设置绘图区域边界框的宽度，以图表宽度的比例表示（从 0 到 1）。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或设置绘图区域边界框的高度，以图表高度的比例表示（从 0 到 1）。读/写 float。

**返回：**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或设置绘图区域边界框的高度，以图表高度的比例表示（从 0 到 1）。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右侧。只读 float。

**返回：**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。只读 float。

**返回：**
float
### getChart() {#getChart--}
```
public final IChart getChart()
```

图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)
### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

定义位置的计算方式：true \\u2013 自动计算；由 X、Y、Width、Height 属性定义。只读 boolean。

**返回：**
boolean
### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

如果手动定义绘图区域的布局，此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。读/写 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Returns:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

如果手动定义绘图区域的布局，此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。读/写 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()


返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)