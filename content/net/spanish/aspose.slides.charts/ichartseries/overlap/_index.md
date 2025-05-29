---
title: Superposición
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica cuánto se superponen las barras y columnas en gráficos 2-D como un porcentaje del -100 al 100. Esta es una propiedad no solo de esta serie, sino de todas las series del grupo de series padre. Es una proyección de la propiedad apropiada en el grupo de series padre y, por lo tanto, esta propiedad es de solo lectura. Para cambiar el valor, utiliza la propiedad de lectura/escritura ParentSeriesGroup.Overlap. SByte de solo lectura.
type: docs
weight: 270
url: /es/aspose.slides.charts/ichartseries/overlap/
---

## Propiedad IChartSeries.Overlap

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es la propiedad no solo de esta serie, sino de todas las series del grupo de series padre. Es una proyección de la propiedad apropiada en el grupo de series padre, y por lo tanto, esta propiedad es de solo lectura. Para cambiar el valor, utiliza la propiedad de lectura/escritura ParentSeriesGroup.Overlap. SByte de solo lectura.

```csharp
public sbyte Overlap { get; }
```

### Comentarios

La superposición especifica el grado de superposición o espacio entre barras y columnas como un porcentaje de su ancho: - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras están colocadas una al lado de la otra sin superposición o espacio. - 100%: Superposición máxima (las barras se superponen completamente entre sí). Esta es una proyección de la propiedad ParentSeriesGroup.Overlap.

### Véase También

* interfaz [IChartSeries](../../ichartseries)
* espacio de nombres [Aspose.Slides.Charts](../../ichartseries)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->