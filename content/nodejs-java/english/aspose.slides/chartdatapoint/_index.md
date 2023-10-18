---
title: ChartDataPoint
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdatapoint/
---

## ChartDataPoint class

 Represents series data point.
 
### getActualHeight {#getActualHeight}

| Name | Description |
| --- | --- |
| getActualHeight () | Specifies actual height of the chart element. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getActualWidth {#getActualWidth}

| Name | Description |
| --- | --- |
| getActualWidth () | Specifies actual width of the chart element. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getActualX {#getActualX}

| Name | Description |
| --- | --- |
| getActualX () | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getActualY {#getActualY}

| Name | Description |
| --- | --- |
| getActualY () | Specifies actual top of the chart element relative to the left top corner of the chart. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getAutomaticDataPointColor {#getAutomaticDataPointColor}

| Name | Description |
| --- | --- |
| getAutomaticDataPointColor () | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. This color is used by default if FillType equals NotDefined. |

 **Result:**
Color


---


### getBubbleSize {#getBubbleSize}

| Name | Description |
| --- | --- |
| getBubbleSize () | BubbleSize. Read-only IDoubleChartValue. |

 **Result:**
[DoubleChartValue](../doublechartvalue)


---


### getColorValue {#getColorValue}

| Name | Description |
| --- | --- |
| getColorValue () | Returns the color value of chart data point. Used with Map charts. Read-only IDoubleChartValue. |

 **Result:**
[DoubleChartValue](../doublechartvalue)


---


### getDataPointLevels {#getDataPointLevels}

| Name | Description |
| --- | --- |
| getDataPointLevels () | Returns container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |

 **Result:**
[ChartDataPointLevelsManager](../chartdatapointlevelsmanager)


---


### getErrorBarsCustomValues {#getErrorBarsCustomValues}

| Name | Description |
| --- | --- |
| getErrorBarsCustomValues () | Represents series error bars values in case of Custom value type. Read-only IErrorBarsCustomValues. |

 **Result:**
[ErrorBarsCustomValues](../errorbarscustomvalues)


---


### getExplosion {#getExplosion}

| Name | Description |
| --- | --- |
| getExplosion () | Specifies the amount the data point shall be moved from the center of the pie. Read/write int. |

 **Result:**
int


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Represents the formatting properties. Read/write IFormat. |

 **Result:**
[Format](../format)


---


### getIndex {#getIndex}

| Name | Description |
| --- | --- |
| getIndex () | Determines which of the parent's children collection this data point applies to. Read long. |

 **Result:**
long


---


### getInvertIfNegative {#getInvertIfNegative}

| Name | Description |
| --- | --- |
| getInvertIfNegative () | Specifies the data point shall invert its colors if the value is negative. Read/write boolean. |

 **Result:**
boolean


---


### getLabel {#getLabel}

| Name | Description |
| --- | --- |
| getLabel () | Label. Read-only IDataLabel. |

 **Result:**
[DataLabel](../datalabel)


---


### getMarker {#getMarker}

| Name | Description |
| --- | --- |
| getMarker () | Specifies a data marker. Read-only IMarker. |

 **Result:**
[Marker](../marker)


---


### getRelatedLegendEntry {#getRelatedLegendEntry}

| Name | Description |
| --- | --- |
| getRelatedLegendEntry () | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Read-only ILegendEntryProperties. |

 **Result:**
[LegendEntryProperties](../legendentryproperties)


---


### getSetAsTotal {#getSetAsTotal}

| Name | Description |
| --- | --- |
| getSetAsTotal () | Sets data point as total. Applied for Waterfall series type only. |

 **Result:**
boolean


---


### getSizeValue {#getSizeValue}

| Name | Description |
| --- | --- |
| getSizeValue () | Returns the size value of chart data point. Used with Treemap and Sunburst charts. Read-only IDoubleChartValue. |

 **Result:**
[DoubleChartValue](../doublechartvalue)


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue () | Value. Read-only IDoubleChartValue. |

 **Result:**
[DoubleChartValue](../doublechartvalue)


---


### getXValue {#getXValue}

| Name | Description |
| --- | --- |
| getXValue () | XValue. Read-only IStringOrDoubleChartValue. |

 **Result:**
[StringOrDoubleChartValue](../stringordoublechartvalue)


---


### getYValue {#getYValue}

| Name | Description |
| --- | --- |
| getYValue () | YValue. Read-only IDoubleChartValue. |

 **Result:**
[DoubleChartValue](../doublechartvalue)


---


### isBubble3D {#isBubble3D}

| Name | Description |
| --- | --- |
| isBubble3D () | Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean. |

 **Result:**
boolean


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes DataPoint from chart series. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if data point is already removed from chart series. |


---


### setBubble3D {#setBubble3D}

| Name | Description |
| --- | --- |
| setBubble3D (boolean) | Specifies that the bubbles have a 3-D effect applied to them. Read/write boolean. |


---


### setExplosion {#setExplosion}

| Name | Description |
| --- | --- |
| setExplosion (int) | Specifies the amount the data point shall be moved from the center of the pie. Read/write int. |


---


### setFormat {#setFormat}

| Name | Description |
| --- | --- |
| setFormat ([Format](../format)) | Represents the formatting properties. Read/write IFormat. |


---


### setInvertIfNegative {#setInvertIfNegative}

| Name | Description |
| --- | --- |
| setInvertIfNegative (boolean) | Specifies the data point shall invert its colors if the value is negative. Read/write boolean. |


---


### setSetAsTotal {#setSetAsTotal}

| Name | Description |
| --- | --- |
| setSetAsTotal (boolean) | Sets data point as total. Applied for Waterfall series type only. |


---


