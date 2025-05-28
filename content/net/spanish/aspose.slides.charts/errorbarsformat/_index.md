---
title: ErrorBarsFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa las barras de error de las series de gráficos. Los valores personalizados de ErrorBars están en IChartDataPointCollection en la propiedad ErrorBarsCustomValues./ichartdatapoint/errorbarscustomvalues.
type: docs
weight: 1590
url: /es/aspose.slides.charts/errorbarsformat/
---

## Clase ErrorBarsFormat

Representa las barras de error de las series de gráficos. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)).

```csharp
public class ErrorBarsFormat : DomObject<ChartSeries>, IErrorBarsFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Chart](../../aspose.slides.charts/errorbarsformat/chart) { get; } | Devuelve el gráfico padre. Solo lectura [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/errorbarsformat/format) { get; set; } | Representa el formato de las barras de error. Lectura/escritura [`IFormat`](../iformat). |
| [HasEndCap](../../aspose.slides.charts/errorbarsformat/hasendcap) { get; set; } | Especifica que no se dibuja un extremo en las barras de error. Lectura/escritura booleano. |
| [IsVisible](../../aspose.slides.charts/errorbarsformat/isvisible) { get; set; } | Obtiene o establece la visibilidad de las barras de error. Lectura/escritura booleano. |
| [Type](../../aspose.slides.charts/errorbarsformat/type) { get; set; } | Obtiene o establece el tipo de barras de error. Lectura/escritura [`ErrorBarType`](../errorbartype). |
| [Value](../../aspose.slides.charts/errorbarsformat/value) { get; set; } | Obtiene o establece el valor que se utiliza con los tipos de valor Fijo, Porcentaje y DesviaciónEstándar para determinar la longitud de las barras de error. En cualquier otro caso, devolverá NaN. Lectura/escritura Single. |
| [ValueType](../../aspose.slides.charts/errorbarsformat/valuetype) { get; set; } | Representa las posibles formas de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor, use la propiedad [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) de un punto de datos específico en la colección DataPoints de la serie. En caso de tipo de valor Fijo, Porcentaje o DesviaciónEstándar, use la propiedad Value para especificar el valor. Lectura/escritura [`ErrorBarValueType`](../errorbarvaluetype). |

### Ver También

* clase [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* clase [ChartSeries](../chartseries)
* interfaz [IErrorBarsFormat](../ierrorbarsformat)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->