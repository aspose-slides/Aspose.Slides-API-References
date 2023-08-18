---
title: ChartPlotArea
second_title: Aspose.Slides for Java API Reference
description: Represents rectangle where chart should be plotted.
type: docs
weight: 93
url: /com.aspose.slides/chartplotarea/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

Represents rectangle where chart should be plotted.
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns the format of a plot area. |
| [getX()](#getX--) | Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). |
| [setX(float value)](#setX-float-) | Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). |
| [getY()](#getY--) | Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). |
| [setY(float value)](#setY-float-) | Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). |
| [getWidth()](#getWidth--) | Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). |
| [setWidth(float value)](#setWidth-float-) | Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). |
| [getHeight()](#getHeight--) | Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). |
| [setHeight(float value)](#setHeight-float-) | Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). |
| [getRight()](#getRight--) | Right. |
| [getBottom()](#getBottom--) | Bottom. |
| [getChart()](#getChart--) | Chart. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | Defines how location should be calculated: true \\u2013 calculated automatically; defined by the X, Y, Width, Height properties. |
| [getLayoutTargetType()](#getLayoutTargetType--) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Returns the format of a plot area. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getX() {#getX--}
```
public final float getX()
```


Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```


Right. Read-only float.

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Bottom. Read-only float.

**Returns:**
float
### getChart() {#getChart--}
```
public final IChart getChart()
```


Chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```


Defines how location should be calculated: true \\u2013 calculated automatically; defined by the X, Y, Width, Height properties. Read-only boolean.

**Returns:**
boolean
### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
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
public final void setLayoutTargetType(int value)
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
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
