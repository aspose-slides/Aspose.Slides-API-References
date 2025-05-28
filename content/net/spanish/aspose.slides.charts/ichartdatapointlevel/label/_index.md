---
title: Etiqueta
second_title: Referencia de la API de Aspose.Slidess para .NET
description: Representa la etiqueta de datos a nivel de punto de datos. Aplicada para tipos de series Treemap y Sunburst. Solo lectura IDataLabelaspose.slides/idatalabel.
type: docs
weight: 20
url: /es/aspose.slides.charts/ichartdatapointlevel/label/
---

## Propiedad IChartDataPointLevel.Label

Representa la etiqueta de datos a nivel de punto de datos. Aplicada para tipos de series Treemap y Sunburst. Solo lectura [`IDataLabel`](../../idatalabel).

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

### Véase También

* interfaz [IDataLabel](../../idatalabel)
* interfaz [IChartDataPointLevel](../../ichartdatapointlevel)
* espacio de nombres [Aspose.Slides.Charts](../../ichartdatapointlevel)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->