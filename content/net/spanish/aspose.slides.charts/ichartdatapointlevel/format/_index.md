---
title: Formato
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa propiedades de formato a nivel de punto de datos. Lectura/escritura IFormataspose.slides.charts/iformat.
type: docs
weight: 10
url: /es/aspose.slides.charts/ichartdatapointlevel/format/
---

## Propiedad IChartDataPointLevel.Format

Representa propiedades de formato a nivel de punto de datos. Lectura/escritura [`IFormat`](../../iformat).

```csharp
public IFormat Format { get; }
```

### Ejemplos

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Treemap, 50, 50, 500, 400);
    IChartSeries series = chart.ChartData.Series[0];

    IChartDataPointLevel dataPointLevel = series.DataPoints[7].DataPointLevels[2];
    dataPointLevel.Format.Fill.FillType = FillType.Solid;
    dataPointLevel.Format.Fill.SolidFillColor.Color = Color.Red;
}
```

### Véase también

* interfaz [IFormat](../../iformat)
* interfaz [IChartDataPointLevel](../../ichartdatapointlevel)
* espacio de nombres [Aspose.Slides.Charts](../../ichartdatapointlevel)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->