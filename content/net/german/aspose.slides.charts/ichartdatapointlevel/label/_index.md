---
title: Label
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein Datenlabel auf Datenpunkthöhe dar. Angewendet bei Treemap- und Sunburst-Serie-Typen. Nur lesbar IDataLabelaspose.slides/idatalabel.
type: docs
weight: 20
url: /de/aspose.slides.charts/ichartdatapointlevel/label/
---

## IChartDataPointLevel.Label-Eigenschaft

Stellt ein Datenlabel auf Datenpunkthöhe dar. Angewendet bei Treemap- und Sunburst-Serie-Typen. Nur lesbar [`IDataLabel`](../../idatalabel).

```csharp
public IDataLabel Label { get; }
```

### Beispiele

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

### Siehe Auch

* Schnittstelle [IDataLabel](../../idatalabel)
* Schnittstelle [IChartDataPointLevel](../../ichartdatapointlevel)
* Namespace [Aspose.Slides.Charts](../../ichartdatapointlevel)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->