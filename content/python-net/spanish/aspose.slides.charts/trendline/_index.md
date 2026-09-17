---
title: Trendline class
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides.charts/trendline/
---
## Trendline clase

Clase que representa la línea de tendencia de la serie del gráfico

El tipo Trendline expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`trendline_name`](/slides/python-net/es/aspose.slides.charts/trendline/trendline_name/) | Obtiene o establece el nombre de la línea de tendencia.<br/>            Lectura/escritura **str**. |
| [`trendline_type`](/slides/python-net/es/aspose.slides.charts/trendline/trendline_type/) | Obtiene o establece el tipo de línea de tendencia.<br/>            Lectura/escritura [`TrendlineType`](/slides/python-net/es/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/es/aspose.slides.charts/trendline/format/) | Representa el formato de la línea de tendencia.<br/>            Lectura/escritura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/es/aspose.slides.charts/trendline/backward/) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes<br/>            de los datos de la serie que está siendo tendida. En gráficos de dispersión y no dispersión, el valor debe ser cualquier no negativo<br/>            valor.<br/>            Lectura/escritura **float**. |
| [`forward`](/slides/python-net/es/aspose.slides.charts/trendline/forward/) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los<br/>            datos de la serie que está siendo tendida. En gráficos de dispersión y no dispersión, el valor debe ser cualquier no negativo<br/>            valor.<br/>            Lectura/escritura **float**. |
| [`intercept`](/slides/python-net/es/aspose.slides.charts/trendline/intercept/) | Especifica el valor donde la línea de tendencia debe cruzar el eje y. Esta propiedad solo será compatible<br/>            cuando el tipo de línea de tendencia sea exp, linear o poly.<br/>            Lectura/escritura **float**. |
| [`display_equation`](/slides/python-net/es/aspose.slides.charts/trendline/display_equation/) | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el Rsquaredvalue).<br/>            Lectura/escritura **bool**. |
| [`order`](/slides/python-net/es/aspose.slides.charts/trendline/order/) | Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6.<br/>            Lectura/escritura **int**. |
| [`period`](/slides/python-net/es/aspose.slides.charts/trendline/period/) | Especifica el período de la línea de tendencia para una línea de tendencia de promedio móvil. Se ignora para otras variantes de línea de tendencia.<br/>            El valor debe estar entre 2 y 255.<br/>            Lectura/escritura **int**. |
| [`display_r_squared_value`](/slides/python-net/es/aspose.slides.charts/trendline/display_r_squared_value/) | Especifica que el valor R-squared de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación).<br/>            Lectura/escritura **bool**. |
| [`related_legend_entry`](/slides/python-net/es/aspose.slides.charts/trendline/related_legend_entry/) | Representa la entrada de la leyenda relacionada con esta línea de tendencia<br/>            Solo lectura [`ILegendEntryProperties`](/slides/python-net/es/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/es/aspose.slides.charts/trendline/text_frame_for_overriding/) | Puede contener texto con formato enriquecido. Si esta propiedad no es None, entonces este <br/>            valor de texto con formato sobrescribe el texto autogenerado de la etiqueta de datos.<br/>            Texto autogenerado de la etiqueta de datos significa el texto que es gestionado por las propiedades ShowSeriesName, <br/>            ShowValue, ... y que se formatea con la propiedad TextFormatManager.TextFormat.<br/>            Solo lectura [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/trendline/text_format/) | Devuelve el formato de texto.<br/>            Solo lectura [`IChartTextFormat`](/slides/python-net/es/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/es/aspose.slides.charts/trendline/chart/) | Devuelve el gráfico padre.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/es/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/trendline/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/es/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Inicializa TextFrameForOverriding con el texto en el parámetro "text".<br/>            Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)