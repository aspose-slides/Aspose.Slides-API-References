---
title: LayoutTargetType
second_title: Aspose.Sildes for .NET API Reference
description: If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside not including axis and axis labels or outside including axis and axis labels. Read/write LayoutTargetTypeaspose.slides.charts/ichartplotarea/layouttargettype.
type: docs
weight: 40
url: /aspose.slides.charts/ichartplotarea/layouttargettype/
---

## IChartPlotArea.LayoutTargetType property

If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write `LayoutTargetType`.

```csharp
public LayoutTargetType LayoutTargetType { get; set; }
```

### Examples

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

### See Also

* enum [LayoutTargetType](../../layouttargettype)
* interface [IChartPlotArea](../../ichartplotarea)
* namespace [Aspose.Slides.Charts](../../ichartplotarea)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
