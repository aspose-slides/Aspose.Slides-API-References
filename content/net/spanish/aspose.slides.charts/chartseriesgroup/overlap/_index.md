---
title: Overlap
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica cuánto se superpondrán las barras y columnas en gráficos 2-D como un porcentaje del -100 al 100. - -100 Máxima separación, las barras están completamente separadas. - 0 Las barras se colocan una al lado de la otra sin superposición ni separación. - 100 Máxima superposición, las barras se superponen completamente. Esta propiedad es de lectura/escritura SByte.
type: docs
weight: 120
url: /es/aspose.slides.charts/chartseriesgroup/overlap/
---

## Propiedad ChartSeriesGroup.Overlap

Especifica cuánto se superpondrán las barras y columnas en gráficos 2-D, como un porcentaje (del -100% al 100%). - -100%: Máxima separación (las barras están completamente separadas). - 0%: Las barras se colocan una al lado de la otra sin superposición ni separación. - 100%: Máxima superposición (las barras se superponen completamente). Esta propiedad es de lectura/escritura SByte.

```csharp
public sbyte Overlap { get; set; }
```

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | Lanzada cuando el valor se establece fuera del rango válido de -100 a 100. |

### Ejemplos

El siguiente ejemplo demuestra cómo establecer la superposición para un grupo de series de gráficos y renderizar el gráfico resultante en un formulario:

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
    IChartSeriesCollection series = chart.ChartData.Series;
    series[0].ParentSeriesGroup.Overlap = 55; // Establecer superposición al 55%

    var image=pres.Slides[0].GetImage(1, 1);
    image.Save("image.png",ImageFormat.Png);
}
```

### Véase También

* clase [ChartSeriesGroup](../../chartseriesgroup)
* espacio de nombres [Aspose.Slides.Charts](../../chartseriesgroup)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->