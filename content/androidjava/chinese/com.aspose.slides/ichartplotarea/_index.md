---
title: IChartPlotArea
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图表标题属性。
type: docs
url: /zh/com.aspose.slides/ichartplotarea/
---
**所有实现的接口：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

表示图表标题属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 返回绘图区的格式。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | 如果绘图区的布局是手动定义的，此属性指定是按内部布局绘图区（不包括坐标轴和坐标轴标签）还是按外部布局绘图区（包括坐标轴和坐标轴标签）。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | 如果绘图区的布局是手动定义的，此属性指定是按内部布局绘图区（不包括坐标轴和坐标轴标签）还是按外部布局绘图区（包括坐标轴和坐标轴标签）。 |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回绘图区的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

如果绘图区的布局是手动定义的，此属性指定是按内部布局绘图区（不包括坐标轴和坐标轴标签）还是按外部布局绘图区（包括坐标轴和坐标轴标签）。读/写 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Returns:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |