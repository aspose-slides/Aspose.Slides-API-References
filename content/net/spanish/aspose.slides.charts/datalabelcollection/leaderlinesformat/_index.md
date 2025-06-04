---
title: LeaderLinesFormat
second_title: Aspose.Slides para .NET Referencia de API
description: Representa el formato de las líneas de líder de las etiquetas de datos. Solo lectura IChartLinesFormataspose.slides/ichartlinesformat.
type: docs
weight: 70
url: /es/aspose.slides.charts/datalabelcollection/leaderlinesformat/
---

## Propiedad DataLabelCollection.LeaderLinesFormat

Representa el formato de las líneas de líder de las etiquetas de datos. Solo lectura [`IChartLinesFormat`](../../ichartlinesformat).

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

### Véase También

* interfaz [IChartLinesFormat](../../ichartlinesformat)
* clase [DataLabelCollection](../../datalabelcollection)
* espacio de nombres [Aspose.Slides.Charts](../../datalabelcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->