---
title: Label
second_title: Aspose.Slides pour .NET Référence de l'API
description: Représente l'étiquette de données au niveau du point de données. Appliqué pour les types de séries Treemap et Sunburst. Lecture seule IDataLabelaspose.slides/idatalabel.
type: docs
weight: 20
url: /fr/aspose.slides.charts/ichartdatapointlevel/label/
---

## IChartDataPointLevel.Label propriété

Représente l'étiquette de données au niveau du point de données. Appliqué pour les types de séries Treemap et Sunburst. Lecture seule [`IDataLabel`](../../idatalabel).

```csharp
public IDataLabel Label { get; }
```

### Exemples

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

### Voir Aussi

* interface [IDataLabel](../../idatalabel)
* interface [IChartDataPointLevel](../../ichartdatapointlevel)
* namespace [Aspose.Slides.Charts](../../ichartdatapointlevel)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->