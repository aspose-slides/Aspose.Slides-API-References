---
title: ErrorBarsFormat class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat clase

Representa las barras de error de una serie de gráfico. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

El tipo ErrorBarsFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/type/) | Obtiene o establece el tipo de barras de error.<br/>            Lectura/escritura [`ErrorBarType`](/slides/python-net/es/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/value_type/) | Representa las posibles formas de determinar la longitud de las barras de error.<br/>            En caso de tipo de valor personalizado, para especificar el valor use la propiedad [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) del punto de datos específico en la colección DataPoints de la serie.<br/>            En caso de tipo de valor Fixed, Percentage o StandardDeviation, use la propiedad Value para especificar el valor.<br/>            Lectura/escritura [`ErrorBarValueType`](/slides/python-net/es/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/has_end_cap/) | Especifica que no se dibuja una tapa final en las barras de error.<br/>            Lectura/escritura **bool**. |
| [`value`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/value/) | Obtiene o establece el valor que se usa con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error.<br/>            En cualquier otro caso devolverá NaN.<br/>            Lectura/escritura **float**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/format/) | Representa el formato de las barras de error.<br/>            Lectura/escritura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/chart/) | Devuelve el gráfico padre.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/is_visible/) | Obtiene o establece la visibilidad de las barras de error.<br/>            Lectura/escritura **bool**. |
| [`slide`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)