---
title: ChartDataPoint
type: docs
weight: 0
url: /php-java/chartdatapoint/
---

# ChartDataPoint class

 Represents series data point.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getActualHeight](/slides/php-java/chartdatapoint/getactualheight/)() | float | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualWidth](/slides/php-java/chartdatapoint/getactualwidth/)() | float | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualX](/slides/php-java/chartdatapoint/getactualx/)() | float | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualY](/slides/php-java/chartdatapoint/getactualy/)() | float | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getAutomaticDataPointColor](/slides/php-java/chartdatapoint/getautomaticdatapointcolor/)() | Color | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried propery and chart style. This color is used by default if FillType equals NotDefined. |
| [getBubbleSize](/slides/php-java/chartdatapoint/getbubblesize/)() | IDoubleChartValue | BubbleSize. Read-only IDoubleChartValue. |
| [getColorValue](/slides/php-java/chartdatapoint/getcolorvalue/)() | IDoubleChartValue | Returns the color value of chart data point. Used with Map charts. Read-only IDoubleChartValue. |
| [getDataPointLevels](/slides/php-java/chartdatapoint/getdatapointlevels/)() | IChartDataPointLevelsManager | Returns container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| [getErrorBarsCustomValues](/slides/php-java/chartdatapoint/geterrorbarscustomvalues/)() | IErrorBarsCustomValues | Represents series error bars values in case of Custom value type. Read-only IErrorBarsCustomValues. |
| [getExplosion](/slides/php-java/chartdatapoint/getexplosion/)() | int | Specifies the amount the data point shall be moved from the center of the pie. Read/write int. |
| [getFormat](/slides/php-java/chartdatapoint/getformat/)() | IFormat | Represents the formatting properties. Read/write IFormat. |
| [getInvertIfNegative](/slides/php-java/chartdatapoint/getinvertifnegative/)() | boolean | Specifies the data point shall invert its colors if the value is negative. Read/write boolean. |
| [getLabel](/slides/php-java/chartdatapoint/getlabel/)() | IDataLabel | Label. Read-only IDataLabel. |
| [getMarker](/slides/php-java/chartdatapoint/getmarker/)() | IMarker | Specifies a data marker. Read-only IMarker. |
| [getRelatedLegendEntry](/slides/php-java/chartdatapoint/getrelatedlegendentry/)() | ILegendEntryProperties | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Read-only ILegendEntryProperties. |
| [getSetAsTotal](/slides/php-java/chartdatapoint/getsetastotal/)() | boolean | Sets data point as total. Applied for Waterfall series type only. |
| [getSizeValue](/slides/php-java/chartdatapoint/getsizevalue/)() | IDoubleChartValue | Returns the size value of chart data point. Used with Treemap and Sunburst charts. Read-only IDoubleChartValue. |
| [getValue](/slides/php-java/chartdatapoint/getvalue/)() | IDoubleChartValue | Value. Read-only IDoubleChartValue. |
| [getXValue](/slides/php-java/chartdatapoint/getxvalue/)() | IStringOrDoubleChartValue | XValue. Read-only IStringOrDoubleChartValue. |
| [getYValue](/slides/php-java/chartdatapoint/getyvalue/)() | IDoubleChartValue | YValue. Read-only IDoubleChartValue. |
| [isBubble3D](/slides/php-java/chartdatapoint/isbubble3d/)() | boolean | Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean. |
| [remove](/slides/php-java/chartdatapoint/remove/)() | void | Removes DataPoint from chart series. |
| [setBubble3D](/slides/php-java/chartdatapoint/setbubble3d/)(boolean) | void | Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean. |
| [setExplosion](/slides/php-java/chartdatapoint/setexplosion/)(int) | void | Specifies the amount the data point shall be moved from the center of the pie. Read/write int. |
| [setFormat](/slides/php-java/chartdatapoint/setformat/)(IFormat) | void | Represents the formatting properties. Read/write IFormat. |
| [setInvertIfNegative](/slides/php-java/chartdatapoint/setinvertifnegative/)(boolean) | void | Specifies the data point shall invert its colors if the value is negative. Read/write boolean. |
| [setSetAsTotal](/slides/php-java/chartdatapoint/setsetastotal/)(boolean) | void | Sets data point as total. Applied for Waterfall series type only. |
