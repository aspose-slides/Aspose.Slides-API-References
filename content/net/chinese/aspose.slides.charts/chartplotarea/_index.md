---
title: ChartPlotArea
second_title: Aspose.Sildes for .NET API Reference
description: 表示图表应该绘制的矩形。
type: docs
weight: 1340
url: /zh/aspose.slides.charts/chartplotarea/
---

## ChartPlotArea class

表示图表应该绘制的矩形。

```csharp
public class ChartPlotArea : DomObject<Chart>, IChartPlotArea
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartplotarea/actualheight) { get; } | 指定图表元素的实际高度。在获取实际值之前调用方法 IChart.ValidateChartLayout()。读取为 Single。 |
| [ActualWidth](../../aspose.slides.charts/chartplotarea/actualwidth) { get; } | 指定图表元素的实际宽度。在获取实际值之前调用方法 IChart.ValidateChartLayout()。读取为 Single。 |
| [ActualX](../../aspose.slides.charts/chartplotarea/actualx) { get; } | 指定图表元素相对于图表左上角的实际 x 位置（左侧）。在获取实际值之前调用方法 IChart.ValidateChartLayout()。读取为 Single。 |
| [ActualY](../../aspose.slides.charts/chartplotarea/actualy) { get; } | 指定图表元素相对于图表左上角的实际顶部位置。在获取实际值之前调用方法 IChart.ValidateChartLayout()。读取为 Single。 |
| [Bottom](../../aspose.slides.charts/chartplotarea/bottom) { get; } | 底部。只读 Single。 |
| [Chart](../../aspose.slides.charts/chartplotarea/chart) { get; } | 图表。只读 [`IChart`](../ichart)。 |
| [Format](../../aspose.slides.charts/chartplotarea/format) { get; } | 返回绘图区域的格式。只读 [`IFormat`](../iformat)。 |
| [Height](../../aspose.slides.charts/chartplotarea/height) { get; set; } | 返回或设置绘图区域边界框的高度，作为图表高度的一个比例（从 0 到 1）。读写 Single。 |
| [IsLocationAutocalculated](../../aspose.slides.charts/chartplotarea/islocationautocalculated) { get; } | 定义位置的计算方式：true - 自动计算；由 X、Y、Width、Height 属性定义。只读 Boolean。 |
| [LayoutTargetType](../../aspose.slides.charts/chartplotarea/layouttargettype) { get; set; } | 如果绘图区域的布局是手动定义的，则该属性指定是否通过内部（不包括坐标轴和坐标轴标签）或外部（包括坐标轴和坐标轴标签）来布局绘图区域。读写 [`LayoutTargetType`](./layouttargettype)。 |
| [Right](../../aspose.slides.charts/chartplotarea/right) { get; } | 右侧。只读 Single。 |
| [Width](../../aspose.slides.charts/chartplotarea/width) { get; set; } | 返回或设置绘图区域边界框的宽度，作为图表宽度的一个比例（从 0 到 1）。读写 Single。 |
| [X](../../aspose.slides.charts/chartplotarea/x) { get; set; } | 返回或设置绘图区域边界框左上角的 x 坐标，作为图表宽度的一个比例（从 0 到 1）。读写 Single。 |
| [Y](../../aspose.slides.charts/chartplotarea/y) { get; set; } | 返回或设置绘图区域边界框左上角的 y 坐标，作为图表高度的一个比例（从 0 到 1）。读写 Single。 |

### 另请参见

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [Chart](../chart)
* interface [IChartPlotArea](../ichartplotarea)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->