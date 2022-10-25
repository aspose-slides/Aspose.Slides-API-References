---
title: IChartPlotArea
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart title properties.
type: docs
weight: 696
url: /androidjava/com.aspose.slides/ichartplotarea/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Represents chart title properties.
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns the format of a plot area. |
| [getLayoutTargetType()](#getLayoutTargetType--) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returns the format of a plot area. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

```
Presentation presentation = new Presentation();
  try
  {
      ISlide slide = presentation.getSlides().get_Item(0);
      IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
      chart.getPlotArea().setX(0.2f);
      chart.getPlotArea().setY(0.2f);
      chart.getPlotArea().setWidth(0.7f);
      chart.getPlotArea().setHeight(0.7f);
      chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
      ...
  } finally {
      if (presentation != null) presentation.dispose();
  }
```

**Returns:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

```
Presentation presentation = new Presentation();
  try
  {
      ISlide slide = presentation.getSlides().get_Item(0);
      IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
      chart.getPlotArea().setX(0.2f);
      chart.getPlotArea().setY(0.2f);
      chart.getPlotArea().setWidth(0.7f);
      chart.getPlotArea().setHeight(0.7f);
      chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
      ...
  } finally {
      if (presentation != null) presentation.dispose();
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

