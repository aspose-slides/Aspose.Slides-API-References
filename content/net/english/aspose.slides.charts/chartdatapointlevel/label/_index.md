---
title: Label
second_title: Aspose.Sildes for .NET API Reference
description: Represents data label of data point level. Applied for Treemap and Sunburst sereis types. Read-only IDataLabelaspose.slides.charts/idatalabel.
type: docs
weight: 20
url: /aspose.slides.charts/chartdatapointlevel/label/
---

## ChartDataPointLevel.Label property

Represents data label of data point level. Applied for Treemap and Sunburst sereis types. Read-only [`IDataLabel`](../../idatalabel).

```csharp
public IDataLabel Label { get; }
```

### Examples

```csharp
using (Presentation pres = new Presentation())

   IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Sunburst, 50, 50, 500, 400);

    IChartSeries series = chart.ChartData.Series[0];

    IChartDataPointLevel dataPointLevel = series.DataPoints[0].DataPointLevels[1];

    dataPointLevel.Label.DataLabelFormat.ShowCategoryName = false;
    dataPointLevel.Label.DataLabelFormat.ShowValue = true;
    dataPointLevel.Label.DataLabelFormat.ShowSeriesName = true;

    dataPointLevel = series.DataPoints[12].DataPointLevels[1];
    dataPointLevel.Label.TextFormat.PortionFormat.FillFormat.FillType = FillType.Solid;
    dataPointLevel.Label.TextFormat.PortionFormat.FillFormat.SolidFillColor.Color = Color.Red;

```

### See Also

* interface [IDataLabel](../../idatalabel)
* class [ChartDataPointLevel](../../chartdatapointlevel)
* namespace [Aspose.Slides.Charts](../../chartdatapointlevel)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
