---
title: ITrendline
second_title: Referencia de la API Aspose.Slides para .NET
description: Clase que representa la línea de tendencia de las series de gráficos
type: docs
weight: 2160
url: /es/aspose.slides.charts/itrendline/
---

## Interfaz ITrendline

Clase que representa la línea de tendencia de las series de gráficos

```csharp
public interface ITrendline : IOverridableText
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIOverridableText](../../aspose.slides.charts/itrendline/asioverridabletext) { get; } | Devuelve la interfaz IOverridableText. Solo lectura [`IOverridableText`](../ioverridabletext). |
| [Backward](../../aspose.slides.charts/itrendline/backward) { get; set; } | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está analizando. En gráficos de dispersión y no de dispersión, el valor debe ser cualquier valor no negativo. Lectura/escritura Double. |
| [DisplayEquation](../../aspose.slides.charts/itrendline/displayequation) { get; set; } | Especifica que la ecuación para la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor R-cuadrado). Lectura/escritura Boolean. |
| [DisplayRSquaredValue](../../aspose.slides.charts/itrendline/displayrsquaredvalue) { get; set; } | Especifica que el valor R-cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Lectura/escritura Boolean. |
| [Format](../../aspose.slides.charts/itrendline/format) { get; set; } | Representa el formato de la línea de tendencia. Lectura/escritura [`IFormat`](../iformat). |
| [Forward](../../aspose.slides.charts/itrendline/forward) { get; set; } | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está analizando. En gráficos de dispersión y no de dispersión, el valor debe ser cualquier valor no negativo. Lectura/escritura Double. |
| [Intercept](../../aspose.slides.charts/itrendline/intercept) { get; set; } | Especifica el valor donde la línea de tendencia cruza el eje y. Esta propiedad solo se admitirá cuando el tipo de línea de tendencia sea exp, lineal o polinómico. Lectura/escritura Double. |
| [Order](../../aspose.slides.charts/itrendline/order) { get; set; } | Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de líneas de tendencia. El valor debe estar entre 2 y 6. Lectura/escritura Byte. |
| [Period](../../aspose.slides.charts/itrendline/period) { get; set; } | Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. Se ignora para otras variantes de líneas de tendencia. El valor debe estar entre 2 y 255. Lectura/escritura Byte. |
| [RelatedLegendEntry](../../aspose.slides.charts/itrendline/relatedlegendentry) { get; } | Representa la entrada de la leyenda relacionada con esta línea de tendencia. Solo lectura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [TrendlineName](../../aspose.slides.charts/itrendline/trendlinename) { get; set; } | Obtiene o establece el nombre de la línea de tendencia. Lectura/escritura String. |
| [TrendlineType](../../aspose.slides.charts/itrendline/trendlinetype) { get; set; } | Obtiene o establece el tipo de línea de tendencia. Lectura/escritura [`TrendlineType`](./trendlinetype). |

### Ver También

* interfaz [IOverridableText](../ioverridabletext)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->