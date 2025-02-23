---
title: IChartSeriesGroup
second_title: Aspose.Slides for .NET API 参考
description: 表示系列组
type: docs
weight: 1810
url: /zh/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

表示系列组。

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | 允许获取基本 IChartComponent 接口。 只读[`IChartComponent`](../ichartcomponent)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | 指定气泡大小值在气泡图上的表示方式。 读/写[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype)。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | 指定气泡图的比例因子（可以是 默认大小的 0% 到 300% 之间）。 读/写Int32。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | 指定圆环图中孔的大小（可以是绘图区域大小的 10% 到 90% 。）。 读/写Byte。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | 获取或设置第一个饼图或圆环图切片的角度， 以度为单位（从上顺时针，从 0 到 360 度）。 读/写UInt16。 |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 以标记宽度的百分比返回或设置 3D 图表中数据系列之间的距离。 读/写UInt16。 |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | 指定条形或列簇之间的间距，以条形或列宽的百分比表示。 读/写UInt16。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | 如果图表有系列线，则为真。应用于堆积条形图和 OfPie 图表。 读/写Boolean。 |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | 指定 HiLowLines 格式。 HiLowLines 应用于 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | 指定系列中的每个数据标记具有不同的颜色。 读/写Boolean。 |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | 获取指定索引处的元素。 |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | 指定二维图表上应重叠多少条形和柱形（从 -100 到 100）。 读/写SByte。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | 指定如何确定饼图或饼图上的第二个饼图或条形图 中的数据点. 读/写[`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | 带有自定义拆分的饼图或饼图的自定义拆分信息。 包含应在饼图或 饼图的第二个饼或条中绘制的数据点。 只读[`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | 指定一个值，用于确定哪些数据点 在饼图或饼图上的第二个饼图或条形图中饼图。 与 PieSplitBy 属性一起使用。 读/写Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | 指示该组的系列是否绘制在辅助轴上。 只读Boolean。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | 指定饼图的第二个饼图或条形图或 饼图条形图的大小，作为第一个饼图大小的百分比（可以 介于 5% 和 200% 之间）。 读/写UInt16。 |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | 返回图表系列的只读集合。 只读[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection)。 |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | 返回此系列组的类型。 只读[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup)。 |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | 提供对折线图或股票图的向上/向下条的访问。 只读[`IUpDownBarsManager`](../iupdownbarsmanager)。 |

### 评论

1) 请参阅 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的摘要和备注。 2）系列组包含一些系列属性，这对于 组中的每个系列（“系列组属性”）是常见的。 ChartSeriesGroup 类中的“系列组属性”是读/写的。 每个“系列组属性”都可以在 ChartSeries 类中具有只读投影。

### 也可以看看

* interface [IChartComponent](../ichartcomponent)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
