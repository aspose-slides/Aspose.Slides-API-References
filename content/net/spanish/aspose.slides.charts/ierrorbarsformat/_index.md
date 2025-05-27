---
title: IErrorBarsFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa las barras de error de las series de gráficos. Los valores personalizados de ErrorBars están en IChartDataPointCollection en la propiedad ErrorBarsCustomValues./ichartdatapoint/errorbarscustomvalues.
type: docs
weight: 2010
url: /es/aspose.slides.charts/ierrorbarsformat/
---

## Interfaz IErrorBarsFormat

Representa las barras de error de las series de gráficos. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)).

```csharp
public interface IErrorBarsFormat : IChartComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ierrorbarsformat/asichartcomponent) { get; } | Devuelve la interfaz IChartComponent. Solo lectura [`IChartComponent`](../ichartcomponent). |
| [Format](../../aspose.slides.charts/ierrorbarsformat/format) { get; set; } | Representa el formato de las barras de error. Lectura/escritura [`IFormat`](../iformat). |
| [HasEndCap](../../aspose.slides.charts/ierrorbarsformat/hasendcap) { get; set; } | Especifica si no se dibuja un extremo en las barras de error. Lectura/escritura Boolean. |
| [IsVisible](../../aspose.slides.charts/ierrorbarsformat/isvisible) { get; set; } | Obtiene o establece la visibilidad de las barras de error. Lectura/escritura Boolean. |
| [Type](../../aspose.slides.charts/ierrorbarsformat/type) { get; set; } | Obtiene o establece el tipo de barras de error. Lectura/escritura [`ErrorBarType`](../errorbartype). |
| [Value](../../aspose.slides.charts/ierrorbarsformat/value) { get; set; } | Obtiene o establece el valor que se utiliza con los tipos de valor Fijo, Porcentaje y DesviaciónEstándar para determinar la longitud de las barras de error. Lectura/escritura Single. |
| [ValueType](../../aspose.slides.charts/ierrorbarsformat/valuetype) { get; set; } | Representa las formas posibles de determinar la longitud de las barras de error. En caso de tipo de valor personalizado, para especificar el valor, utiliza la propiedad [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) de un punto de datos específico en la colección DataPoints de la serie. Lectura/escritura [`ErrorBarValueType`](../errorbarvaluetype). |

### Vea También

* interfaz [IChartComponent](../ichartcomponent)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->