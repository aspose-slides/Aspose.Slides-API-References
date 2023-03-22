---
title: ChartDataPoint
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/chartdatapoint/
---

## ChartDataPoint class

 Represents series data point.
 

## Methods

| Name | Description |
| --- | --- |
| [getActualHeight](getactualheight)() | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualWidth](getactualwidth)() | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualX](getactualx)() | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualY](getactualy)() | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getAutomaticDataPointColor](getautomaticdatapointcolor)() | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. This color is used by default if FillType equals NotDefined. |
| [getBubbleSize](getbubblesize)() | BubbleSize. Read-only IDoubleChartValue. |
| [getColorValue](getcolorvalue)() | Returns the color value of chart data point. Used with Map charts. Read-only IDoubleChartValue. |
| [getDataPointLevels](getdatapointlevels)() | Returns container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| [getErrorBarsCustomValues](geterrorbarscustomvalues)() | Represents series error bars values in case of Custom value type. Read-only IErrorBarsCustomValues. |
| [getExplosion](getexplosion)() | Specifies the amount the data point shall be moved from the center of the pie. Read/write int. |
| [getFormat](getformat)() | Represents the formatting properties. Read/write IFormat. |
| [getIndex](getindex)() | Determines which of the parent's children collection this data point applies to. Read long. |
| [getInvertIfNegative](getinvertifnegative)() | Specifies the data point shall invert its colors if the value is negative. Read/write boolean. |
| [getLabel](getlabel)() | Label. Read-only IDataLabel. |
| [getMarker](getmarker)() | Specifies a data marker. Read-only IMarker. |
| [getRelatedLegendEntry](getrelatedlegendentry)() | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Read-only ILegendEntryProperties. |
| [getSetAsTotal](getsetastotal)() | Sets data point as total. Applied for Waterfall series type only. |
| [getSizeValue](getsizevalue)() | Returns the size value of chart data point. Used with Treemap and Sunburst charts. Read-only IDoubleChartValue. |
| [getValue](getvalue)() | Value. Read-only IDoubleChartValue. |
| [getXValue](getxvalue)() | XValue. Read-only IStringOrDoubleChartValue. |
| [getYValue](getyvalue)() | YValue. Read-only IDoubleChartValue. |
| [isBubble3D](isbubble3d)() | Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean. |
| [remove](remove)() | Removes DataPoint from chart series. |
| [setBubble3D](setbubble3d)(boolean) | Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean. |
| [setExplosion](setexplosion)(int) | Specifies the amount the data point shall be moved from the center of the pie. Read/write int. |
| [setFormat](setformat)([Format](../format)) | Represents the formatting properties. Read/write IFormat. |
| [setInvertIfNegative](setinvertifnegative)(boolean) | Specifies the data point shall invert its colors if the value is negative. Read/write boolean. |
| [setSetAsTotal](setsetastotal)(boolean) | Sets data point as total. Applied for Waterfall series type only. |
