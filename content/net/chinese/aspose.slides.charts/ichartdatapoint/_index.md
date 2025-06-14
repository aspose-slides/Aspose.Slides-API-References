---
title: IChartDataPoint
second_title: Aspose.Sildes for .NET API Reference
description: 表示系列数据点。
type: docs
weight: 1740
url: /zh/aspose.slides.charts/ichartdatapoint/
---

## IChartDataPoint 接口

表示系列数据点。

```csharp
public interface IChartDataPoint : IActualLayout
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | 返回 IActualLayout 接口。 |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | 返回图表数据点的气泡大小。只读 [`IDoubleChartValue`](../idoublechartvalue)。 |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | 返回图表数据点的颜色值。用于地图图表。只读 [`IDoubleChartValue`](../idoublechartvalue)。 |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | 返回数据点级别的容器。适用于树图和旭日图系列。数据点级别索引为零基。 |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | 表示系列误差条值（自定义值类型）。只读 [`IErrorBarsCustomValues`](../ierrorbarscustomvalues)。 |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | 指定数据点应从饼图中心移动的量。读写 Int32。 |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | 表示格式属性。读写 [`IFormat`](../iformat)。 |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | 确定此数据点适用于父级子集合中的哪个项。只读 UInt32。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | 指定数据点在值为负时应反转颜色。读写布尔值。 |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | 指定气泡应用了 3D 效果。读写布尔值。 |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | 表示图表数据点的标签。只读 [`IDataLabel`](../idatalabel)。 |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | 指定数据标记。只读 [`IMarker`](../imarker)。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | 对应图例项的属性，适用于此列表中的图表类型： ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | 将数据点设置为总计。仅适用于瀑布系列类型。 |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | 返回图表数据点的大小值。用于树图和旭日图。只读 [`IDoubleChartValue`](../idoublechartvalue)。 |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | 返回图表数据点的值。只读 [`IDoubleChartValue`](../idoublechartvalue)。 |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | 返回图表数据点的 x 值。只读 [`IStringOrDoubleChartValue`](../istringordoublechartvalue)。 |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | 返回图表数据点的 y 值。只读 [`IDoubleChartValue`](../idoublechartvalue)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动数据点颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | 从图表系列中移除数据点。 |

### 另请参见

* 接口 [IActualLayout](../iactuallayout)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->