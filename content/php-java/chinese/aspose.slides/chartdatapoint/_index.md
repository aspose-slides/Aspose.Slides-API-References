---
title: ChartDataPoint
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartdatapoint/
---
## ChartDataPoint 类

 表示系列数据点。
 
### getActualHeight {#getActualHeight}

| 名称 | 描述 |
| --- | --- |
| getActualHeight () | 指定图表元素的实际高度。调用方法 IChart.ValidateChartLayout() 以获取实际值。读取 float。 |

 **返回：**
float


---


### getActualWidth {#getActualWidth}

| 名称 | 描述 |
| --- | --- |
| getActualWidth () | 指定图表元素的实际宽度。调用方法 IChart.ValidateChartLayout() 以获取实际值。读取 float。 |

 **返回：**
float


---


### getActualX {#getActualX}

| 名称 | 描述 |
| --- | --- |
| getActualX () | 指定图表元素相对于图表左上角的实际 X 位置（左）。调用方法 IChart.ValidateChartLayout() 以获取实际值。读取 float。 |

 **返回：**
float


---


### getActualY {#getActualY}

| 名称 | 描述 |
| --- | --- |
| getActualY () | 指定图表元素相对于图表左上角的实际顶部位置。调用方法 IChart.ValidateChartLayout() 以获取实际值。读取 float。 |

 **返回：**
float


---


### getAutomaticDataPointColor {#getAutomaticDataPointColor}

| 名称 | 描述 |
| --- | --- |
| getAutomaticDataPointColor () | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

 **返回：**
Color


---


### getBubbleSize {#getBubbleSize}

| 名称 | 描述 |
| --- | --- |
| getBubbleSize () | BubbleSize。只读 IDoubleChartValue。 |

 **返回：**
[DoubleChartValue](../doublechartvalue)


---


### getColorValue {#getColorValue}

| 名称 | 描述 |
| --- | --- |
| getColorValue () | 返回图表数据点的颜色值。用于地图图表。只读 IDoubleChartValue。 |

 **返回：**
[DoubleChartValue](../doublechartvalue)


---


### getDataPointLevels {#getDataPointLevels}

| 名称 | 描述 |
| --- | --- |
| getDataPointLevels () | 返回数据点层级的容器。适用于 Treeamp 和 Sunburst 系列。数据点层级索引从零开始。 |

 **返回：**
[ChartDataPointLevelsManager](../chartdatapointlevelsmanager)


---


### getErrorBarsCustomValues {#getErrorBarsCustomValues}

| 名称 | 描述 |
| --- | --- |
| getErrorBarsCustomValues () | 表示自定义值类型情况下的系列误差棒值。只读 IErrorBarsCustomValues。 |

 **返回：**
[ErrorBarsCustomValues](../errorbarscustomvalues)


---


### getExplosion {#getExplosion}

| 名称 | 描述 |
| --- | --- |
| getExplosion () | 指定数据点应从饼图中心移动的距离。可读写 int。 |

 **返回：**
int


---


### getFormat {#getFormat}

| 名称 | 描述 |
| --- | --- |
| getFormat () | 表示格式化属性。可读写 IFormat。 |

 **返回：**
[Format](../format)


---


### getIndex {#getIndex}

| 名称 | 描述 |
| --- | --- |
| getIndex () |  |

 **返回：**
long


---


### getInvertIfNegative {#getInvertIfNegative}

| 名称 | 描述 |
| --- | --- |
| getInvertIfNegative () | 指定当值为负时，数据点应反转其颜色。可读写 boolean。 |

 **返回：**
boolean


---


### getLabel {#getLabel}

| 名称 | 描述 |
| --- | --- |
| getLabel () | Label。只读 IDataLabel。 |

 **返回：**
[DataLabel](../datalabel)


---


### getMarker {#getMarker}

| 名称 | 描述 |
| --- | --- |
| getMarker () | 指定数据标记。只读 IMarker。 |

 **返回：**
[Marker](../marker)


---


### getRelatedLegendEntry {#getRelatedLegendEntry}

| 名称 | 描述 |
| --- | --- |
| getRelatedLegendEntry () | 对应图例条目的属性，适用于以下图表类型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。只读 ILegendEntryProperties。 |

 **返回：**
[LegendEntryProperties](../legendentryproperties)


---


### getSetAsTotal {#getSetAsTotal}

| 名称 | 描述 |
| --- | --- |
| getSetAsTotal () | 将数据点设为总计。仅适用于 Waterfall 系列类型。 |

 **返回：**
boolean


---


### getSizeValue {#getSizeValue}

| 名称 | 描述 |
| --- | --- |
| getSizeValue () | 返回图表数据点的大小值。用于 Treemap 和 Sunburst 图表。只读 IDoubleChartValue。 |

 **返回：**
[DoubleChartValue](../doublechartvalue)


---


### getValue {#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue () | Value。只读 IDoubleChartValue。 |

 **返回：**
[DoubleChartValue](../doublechartvalue)


---


### getXValue {#getXValue}

| 名称 | 描述 |
| --- | --- |
| getXValue () | XValue。只读 IStringOrDoubleChartValue。 |

 **返回：**
[StringOrDoubleChartValue](../stringordoublechartvalue)


---


### getYValue {#getYValue}

| 名称 | 描述 |
| --- | --- |
| getYValue () | YValue。只读 IDoubleChartValue。 |

 **返回：**
[DoubleChartValue](../doublechartvalue)


---


### isBubble3D {#isBubble3D}

| 名称 | 描述 |
| --- | --- |
| isBubble3D () | 指定气泡是否应用 3-D 效果。可读写 boolean。 |

 **返回：**
boolean


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove () | 从图表系列中删除 DataPoint。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | PptxEditException | 当数据点已从图表系列中删除时抛出。 |


---


### setBubble3D {#setBubble3D}

| 名称 | 描述 |
| --- | --- |
| setBubble3D (boolean) | 指定气泡是否应用 3-D 效果。可读写 boolean。 |

 **返回：**
void


---


### setExplosion {#setExplosion}

| 名称 | 描述 |
| --- | --- |
| setExplosion (int) | 指定数据点应从饼图中心移动的距离。可读写 int。 |

 **返回：**
void


---


### setFormat {#setFormat}

| 名称 | 描述 |
| --- | --- |
| setFormat ([Format](../format)) | 表示格式化属性。可读写 IFormat。 |

 **返回：**
void


---


### setInvertIfNegative {#setInvertIfNegative}

| 名称 | 描述 |
| --- | --- |
| setInvertIfNegative (boolean) | 指定当值为负时，数据点应反转其颜色。可读写 boolean。 |

 **返回：**
void


---


### setSetAsTotal {#setSetAsTotal}

| 名称 | 描述 |
| --- | --- |
| setSetAsTotal (boolean) | 将数据点设为总计。仅适用于 Waterfall 系列类型。 |

 **返回：**
void


---