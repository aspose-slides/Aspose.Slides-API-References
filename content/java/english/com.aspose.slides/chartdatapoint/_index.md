---
title: ChartDataPoint
second_title: Aspose.Slides for Java API Reference
description: Represents series data point.
type: docs
url: /com.aspose.slides/chartdatapoint/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Represents series data point.
## Methods

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returns the size value of chart data point. |
| [getColorValue()](#getColorValue--) | Returns the color value of chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specifies that the bubbles have a 3-D effect applied to them. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifies that the bubbles have a 3-D effect applied to them. |
| [getExplosion()](#getExplosion--) | Specifies the amount the data point shall be moved from the center of the pie. |
| [setExplosion(int value)](#setExplosion-int-) | Specifies the amount the data point shall be moved from the center of the pie. |
| [getFormat()](#getFormat--) | Represents the formatting properties. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the formatting properties. |
| [getMarker()](#getMarker--) | Specifies a data marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Sets data point as total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sets data point as total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Removes DataPoint from chart series. |
| [getDataPointLevels()](#getDataPointLevels--) | Returns container of data point levels. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the data point shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the data point shall invert its colors if the value is negative. |
| [getCachedValue()](#getCachedValue--) | Gets the cached value of a chart data point. |
| [getCachedXValue()](#getCachedXValue--) | Gets the cached X value of a chart data point. |
| [getCachedYValue()](#getCachedYValue--) | Gets the cached Y value of a chart data point. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Gets the cached bubble size of a chart data point. |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Read-only [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Returns:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Returns the size value of chart data point. Used with Treemap and Sunburst charts. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Returns the color value of chart data point. Used with Map charts. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Represents series error bars values in case of Custom value type. Read-only [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Returns:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Read-only [IDataLabel](../../com.aspose.slides/idatalabel).

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean.

**Returns:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Specifies the amount the data point shall be moved from the center of the pie. Read/write int.

**Returns:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Specifies the amount the data point shall be moved from the center of the pie. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Represents the formatting properties. Read/write [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Represents the formatting properties. Read/write [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Specifies a data marker. Read-only [IMarker](../../com.aspose.slides/imarker).

**Returns:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Sets data point as total. Applied for Waterfall series type only.

**Returns:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Sets data point as total. Applied for Waterfall series type only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Removes DataPoint from chart series.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Returns container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based.

**Returns:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Returns:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```


Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. This color is used by default if FillType equals NotDefined.

**Returns:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Specifies the data point shall invert its colors if the value is negative. Read/write boolean.

**Returns:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Specifies the data point shall invert its colors if the value is negative. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


Gets the cached value of a chart data point. Read-only [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print all cached values of the chart series.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```


Gets the cached X value of a chart data point. Read-only [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print all cached X values of the chart series.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```


Gets the cached Y value of a chart data point. Read-only [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print all cached Y values of the chart series.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```


Gets the cached bubble size of a chart data point. Read-only [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print all cached bubble size values of the chart series.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
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
