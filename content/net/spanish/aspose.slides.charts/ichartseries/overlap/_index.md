---
title: Overlap
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica cuánto se superponen las barras y columnas en gráficos 2-D como un porcentaje de -100 a 100. Esta es una propiedad no solo de esta serie, sino de todas las series del grupo de series padre. Es una proyección de la propiedad correspondiente en el grupo de series padre y, por lo tanto, esta propiedad es de solo lectura. Para cambiar el valor, utiliza la propiedad de lectura/escritura ParentSeriesGroup.Overlap. SByte de solo lectura.
type: docs
weight: 270
url: /es/aspose.slides.charts/ichartseries/overlap/
---

## Propiedad IChartSeries.Overlap

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es la propiedad no solo de esta serie, sino de todas las series del grupo de series padre. Es una proyección de la propiedad correspondiente en el grupo de series padre, y por lo tanto, esta propiedad es de solo lectura. Para cambiar el valor, utiliza la propiedad de lectura/escritura ParentSeriesGroup.Overlap. SByte de solo lectura.

```csharp
public sbyte Overlap { get; }
```

### Observaciones

Overlap especifica el grado de superposición o espaciado entre barras y columnas como un porcentaje de su ancho: - -100%: Espaciado máximo (las barras están completamente separadas). - 0%: Las barras están colocadas una al lado de la otra sin superposición ni espaciado. - 100%: Superposición máxima (las barras se superponen completamente). Esta es una proyección de la propiedad ParentSeriesGroup.Overlap.

### Véase también

* interfaz [IChartSeries](../../ichartseries)
* espacio de nombres [Aspose.Slides.Charts](../../ichartseries)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->