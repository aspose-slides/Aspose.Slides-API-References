---
title: Etiqueta
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la etiqueta de datos a nivel de punto de datos. Aplicable para los tipos de series Treemap y Sunburst. Solo lectura IDataLabelaspose.slides/idatalabel.
type: docs
weight: 20
url: /es/aspose.slides.charts/chartdatapointlevel/label/
---

## Propiedad ChartDataPointLevel.Label

Representa la etiqueta de datos a nivel de punto de datos. Aplicable para los tipos de series Treemap y Sunburst. Solo lectura [`IDataLabel`](../../idatalabel).

```csharp
public IDataLabel Label { get; }
```

### Ejemplos

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

### Véase también

* interfaz [IDataLabel](../../idatalabel)
* clase [ChartDataPointLevel](../../chartdatapointlevel)
* espacio de nombres [Aspose.Slides.Charts](../../chartdatapointlevel)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->