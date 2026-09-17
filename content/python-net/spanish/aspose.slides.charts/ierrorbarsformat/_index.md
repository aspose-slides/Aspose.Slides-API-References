---
title: IErrorBarsFormat class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat clase

Representa las barras de error de una serie de gráfico. Los valores personalizados de ErrorBars están en IChartDataPointCollection (en la propiedad [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

El tipo IErrorBarsFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/type/) | Obtiene o establece el tipo de barras de error. <br/> Lectura/escritura [`ErrorBarType`](/slides/python-net/es/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/value_type/) | Representa las formas posibles de determinar la longitud de las barras de error. <br/> En caso de tipo de valor personalizado para especificar el valor use la propiedad [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) del punto de datos específico en la colección DataPoints de la serie. <br/> Lectura/escritura [`ErrorBarValueType`](/slides/python-net/es/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/has_end_cap/) | Especifica que no se dibuja una tapa final en las barras de error.<br/> Lectura/escritura **bool**. |
| [`value`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/value/) | Obtiene o establece el valor que se usa con los tipos de valor Fixed, Percentage y StandardDeviation para determinar la longitud de las barras de error. <br/> Lectura/escritura **float**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/format/) | Representa el formato de las barras de error.<br/> Lectura/escritura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/is_visible/) | Obtiene o establece la visibilidad de las barras de error.<br/> Lectura/escritura **bool**. |
| [`chart`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/chart/) |  |
| [`slide`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/ierrorbarsformat/presentation/) |  |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)