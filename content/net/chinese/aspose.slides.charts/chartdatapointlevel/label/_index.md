---
title: Label
second_title: Aspose.Slides for .NET API 参考
description: 表示数据点级别的数据标签适用于 Treemap 和 Sunburst sereis 类型 只读IDataLabelaspose.slides.charts/idatalabel
type: docs
weight: 20
url: /zh/aspose.slides.charts/chartdatapointlevel/label/
---
## ChartDataPointLevel.Label property

表示数据点级别的数据标签。适用于 Treemap 和 Sunburst sereis 类型。 只读[`IDataLabel`](../../idatalabel)。

```csharp
public IDataLabel Label { get; }
```

### 例子

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

### 也可以看看

* interface [IDataLabel](../../idatalabel)
* class [ChartDataPointLevel](../../chartdatapointlevel)
* 命名空间 [Aspose.Slides.Charts](../../chartdatapointlevel)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
