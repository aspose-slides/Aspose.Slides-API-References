---
title: ChartDataPoint
second_title: Aspose.Slides for .NET API 参考
description: 表示系列数据点
type: docs
weight: 1190
url: /zh/net/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint class

表示系列数据点。

```csharp
public class ChartDataPoint : IChartDataPoint
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | 指定图表元素的实际高度。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 读取Single。 |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | 指定图表元素的实际宽度。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 读取Single。 |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | 指定图表元素相对于图表左上角的实际 x 位置（左侧）。 在获取实际值之前调用方法 IChart.ValidateChartLayout()。 读取Single。 |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | 指定相对于图表左上角的图表元素的实际顶部。 在获取实际值之前调用方法 IChart.ValidateChartLayout()。 读取Single。 |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize。 只读[`IDoubleChartValue`](../idoublechartvalue)。 |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | 返回图表数据点的颜色值。 与地图一起使用。 只读[`IDoubleChartValue`](../idoublechartvalue)。 |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | 返回数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。 数据点级别索引是从零开始的。 |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | 表示自定义值类型的系列误差线值。 只读[`IErrorBarsCustomValues`](../ierrorbarscustomvalues)。 |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | 指定数据点应从饼图中心移动的量。 读/写Int32。 |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | 表示格式化属性。 读/写[`IFormat`](../iformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | 指定如果值为负数，数据点应反转其颜色。 读/写Boolean。 |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | 指定对气泡应用 3-D 效果。 读/写Boolean。 |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | 标签。 只读[`IDataLabel`](../idatalabel)。 |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | 指定数据标记。 只读[`IMarker`](../imarker)。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | 此列表中图表类型的相应图例条目的属性: ChartType.BarOfPie, ChartType.ExplodedPie , ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。 只读[`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | 将数据点设置为总数。仅适用于瀑布系列类型。 |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | 返回图表数据点的大小值。 与 Treemap 和 Sunburst 图表一起使用。 只读[`IDoubleChartValue`](../idoublechartvalue)。 |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | 值。 只读[`IDoubleChartValue`](../idoublechartvalue)。 |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue。 只读[`IStringOrDoubleChartValue`](../istringordoublechartvalue)。 |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | Y 值。 只读[`IDoubleChartValue`](../idoublechartvalue)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | 根据系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式返回数据点的自动颜色。 如果 FillType 等于 NotDefined，则默认使用此颜色。 |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | 从图表系列中删除数据点。 |

### 也可以看看

* interface [IChartDataPoint](../ichartdatapoint)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->