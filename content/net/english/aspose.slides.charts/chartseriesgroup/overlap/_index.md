---
title: Overlap
second_title: Aspose.Sildes for .NET API Reference
description: Specifies how much bars and columns shall overlap on 2-D charts as a percentage from -100 to 100. - -100 Maximum spacing bars are completely separated. - 0 Bars are placed side by side without overlap or spacing. - 100 Maximum overlap bars completely overlap each other. This property is read/write SByte.
type: docs
weight: 120
url: /aspose.slides.charts/chartseriesgroup/overlap/
---

## ChartSeriesGroup.Overlap property

Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This property is read/write SByte.

```csharp
public sbyte Overlap { get; set; }
```

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the value is set outside the valid range of -100 to 100. |

### Examples

The following example demonstrates how to set the overlap for a chart series group and render the resulting chart on a form:

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
    IChartSeriesCollection series = chart.ChartData.Series;
    series[0].ParentSeriesGroup.Overlap = 55; // Set overlap to 55%

    var image=pres.Slides[0].GetImage(1, 1);
    image.Save("image.png",ImageFormat.Png);
}
```

### See Also

* class [ChartSeriesGroup](../../chartseriesgroup)
* namespace [Aspose.Slides.Charts](../../chartseriesgroup)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
