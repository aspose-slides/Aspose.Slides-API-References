---
title: IChartDataPoint
second_title: Aspose.Slides for Java API Reference
description: Represents series data point.
type: docs
url: /com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Represents series data point.
## Methods

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | Gets the x value of a chart data point. |
| [getYValue()](#getYValue--) | Gets the y value of a chart data point. |
| [getBubbleSize()](#getBubbleSize--) | Gets the bubble size of a chart data point. |
| [getValue()](#getValue--) | Gets the value of a chart data point. |
| [getCachedXValue()](#getCachedXValue--) | Gets the cached X value of a chart data point. |
| [getCachedYValue()](#getCachedYValue--) | Gets the cached Y value of a chart data point. |
| [getCachedValue()](#getCachedValue--) | Gets the cached value of a chart data point. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Gets the cached bubble size of a chart data point. |
| [getSizeValue()](#getSizeValue--) | Gets the size value of a chart data point. |
| [getColorValue()](#getColorValue--) | Gets the color value of a chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Represents the lable of chart data point. |
| [isBubble3D()](#isBubble3D--) | Specifies that the bubbles have a 3-D effect applied to them. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifies that the bubbles have a 3-D effect applied to them. |
| [getExplosion()](#getExplosion--) | Specifies the amount the data point shall be moved from the center of the pie. |
| [setExplosion(int value)](#setExplosion-int-) | Specifies the amount the data point shall be moved from the center of the pie. |
| [getFormat()](#getFormat--) | Represents the formatting properties. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the formatting properties. |
| [getMarker()](#getMarker--) | Specifies a data marker. |
| [remove()](#remove--) | Removes DataPoint from chart series. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Sets data point as total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sets data point as total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the data point shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the data point shall invert its colors if the value is negative. |
| [getDataPointLevels()](#getDataPointLevels--) | Returns container of data point levels. |
| [getIndex()](#getIndex--) | Determines which of the parent's children collection this data point applies to. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Gets the x value of a chart data point. Read-only [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Returns:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Gets the y value of a chart data point. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Gets the bubble size of a chart data point. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Gets the value of a chart data point. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
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
public abstract ICachedChartValue getCachedYValue()
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
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
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
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
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
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Gets the size value of a chart data point. Used with Treemap and Sunburst charts. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Gets the color value of a chart data point. Used with Map charts. Read-only [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returns:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Represents series error bars values in case of Custom value type. Read-only [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Returns:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Represents the lable of chart data point. Read-only [IDataLabel](../../com.aspose.slides/idatalabel).

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean.

**Returns:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Specifies the amount the data point shall be moved from the center of the pie. Read/write int.

**Returns:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Specifies the amount the data point shall be moved from the center of the pie. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Represents the formatting properties. Read/write [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Represents the formatting properties. Read/write [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Specifies a data marker. Read-only [IMarker](../../com.aspose.slides/imarker).

**Returns:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


Removes DataPoint from chart series.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. This color is used by default if FillType equals NotDefined.

**Returns:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Sets data point as total. Applied for Waterfall series type only.

**Returns:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Sets data point as total. Applied for Waterfall series type only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Specifies the data point shall invert its colors if the value is negative. Read/write boolean.

**Returns:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Specifies the data point shall invert its colors if the value is negative. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Returns container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based.

**Returns:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Determines which of the parent's children collection this data point applies to. Read long.

**Returns:**
long
