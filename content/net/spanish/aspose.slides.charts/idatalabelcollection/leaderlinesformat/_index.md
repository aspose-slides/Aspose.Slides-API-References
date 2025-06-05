---
title: LeaderLinesFormat
second_title: Aspose.Slides para .NET Referencia de API
description: Representa el formato de líneas guías de etiquetas de datos. Solo lectura IChartLinesFormat aspose.slides.charts/ichartlinesformat.
type: docs
weight: 80
url: /es/aspose.slides.charts/idatalabelcollection/leaderlinesformat/
---

## Propiedad IDataLabelCollection.LeaderLinesFormat

Representa el formato de líneas guías de etiquetas de datos. Solo lectura [`IChartLinesFormat`](../../ichartlinesformat).

```csharp
public IChartLinesFormat LeaderLinesFormat { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IChart chart = (IChart) pres.Slides[0].Shapes[0];
    IChartSeriesCollection series = chart.ChartData.Series;
    IDataLabelCollection labels = series[0].Labels;

    labels.LeaderLinesFormat.Line.FillFormat.FillType = FillType.Solid;
    labels.LeaderLinesFormat.Line.FillFormat.SolidFillColor.Color = Color.FromArgb(255, 255, 0, 0);
}
```

### Ver También

* interfaz [IChartLinesFormat](../../ichartlinesformat)
* interfaz [IDataLabelCollection](../../idatalabelcollection)
* espacio de nombres [Aspose.Slides.Charts](../../idatalabelcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->