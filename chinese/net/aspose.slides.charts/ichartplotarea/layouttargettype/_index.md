---
title: LayoutTargetType
second_title: Aspose.Slides for .NET API 参考
description: 如果手动定义绘图区域的布局此属性指定 是否按内部布局绘图区域不包括轴和轴标签或在 之外包括轴和轴标签 读/写LayoutTargetTypeaspose.slides.charts/ichartplotarea/layouttargettype
type: docs
weight: 40
url: /zh/net/aspose.slides.charts/ichartplotarea/layouttargettype/
---
## IChartPlotArea.LayoutTargetType property

如果手动定义绘图区域的布局，此属性指定 是否按内部布局绘图区域（不包括轴和轴标签）或在 之外（包括轴和轴标签）。 读/写`LayoutTargetType`。

```csharp
public LayoutTargetType LayoutTargetType { get; set; }
```

### 例子

```csharp
using (Presentation presentation = new Presentation())

    ISlide slide = presentation.Slides[0];
    IChart chart = slide.Shapes.AddChart(ChartType.ClusteredColumn, 20, 100, 600, 400);

    chart.PlotArea.AsILayoutable.X = 0.2f;
    chart.PlotArea.AsILayoutable.Y = 0.2f;
    chart.PlotArea.AsILayoutable.Width = 0.7f;
    chart.PlotArea.AsILayoutable.Height = 0.7f;

    chart.PlotArea.LayoutTargetType = LayoutTargetType.Inner;
    ...

```

### 也可以看看

* enum [LayoutTargetType](../../layouttargettype)
* interface [IChartPlotArea](../../ichartplotarea)
* 命名空间 [Aspose.Slides.Charts](../../ichartplotarea)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->