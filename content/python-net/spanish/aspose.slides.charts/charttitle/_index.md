---
title: ChartTitle class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/charttitle/
---
## ChartTitle clase

Representa las propiedades del título del gráfico.

El tipo ChartTitle expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/es/aspose.slides.charts/charttitle/x/) | Devuelve o establece la coordenada x de un título como una fracción del ancho del gráfico.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides.charts/charttitle/y/) | Devuelve o establece la coordenada y de un título como una fracción de la altura del gráfico.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides.charts/charttitle/width/) | Devuelve o establece el ancho de un título como una fracción del ancho del gráfico.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides.charts/charttitle/height/) | Devuelve o establece la altura de un título como una fracción de la altura del gráfico.<br/>            Lectura/escritura **float**. |
| [`right`](/slides/python-net/es/aspose.slides.charts/charttitle/right/) | Derecha.<br/>            Solo lectura **float**. |
| [`bottom`](/slides/python-net/es/aspose.slides.charts/charttitle/bottom/) | Inferior.<br/>            Solo lectura **float**. |
| [`overlay`](/slides/python-net/es/aspose.slides.charts/charttitle/overlay/) | Determina si otros elementos del gráfico pueden superponerse al título.<br/>            Lectura/escritura **bool**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/charttitle/format/) | Devuelve los estilos de relleno, línea y efecto de un título.<br/>            Solo lectura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/es/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Puede contener un texto con formato enriquecido. Si esta propiedad no es None, entonces este <br/>            valor de texto con formato sobrescribe el texto autogenerado.<br/>            El texto autogenerado es una propiedad implícita de la etiqueta de datos, la etiqueta de unidad de visualización del eje de valores, el título del eje, el título del gráfico, la etiqueta de la línea de tendencia.<br/>            El texto autogenerado se formatea con la propiedad IFormattedTextContainer.TextFormat.<br/>            Solo lectura [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/charttitle/text_format/) | Devuelve el formato de texto.<br/>            Solo lectura [`IChartTextFormat`](/slides/python-net/es/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/es/aspose.slides.charts/charttitle/actual_x/) | Especifica la ubicación x real (izquierda) del elemento del gráfico respecto a la esquina superior izquierda del gráfico.<br/>            Llama al método IChart.ValidateChartLayout() antes para obtener valores reales.<br/>            Lectura **float**. |
| [`actual_y`](/slides/python-net/es/aspose.slides.charts/charttitle/actual_y/) | Especifica la parte superior real del elemento del gráfico respecto a la esquina superior izquierda del gráfico.<br/>            Llama al método IChart.ValidateChartLayout() antes para obtener valores reales.<br/>            Lectura **float**. |
| [`actual_width`](/slides/python-net/es/aspose.slides.charts/charttitle/actual_width/) | Especifica el ancho real del elemento del gráfico. Llama al método IChart.ValidateChartLayout() antes para obtener valores reales.<br/>            Lectura **float**. |
| [`actual_height`](/slides/python-net/es/aspose.slides.charts/charttitle/actual_height/) | Especifica la altura real del elemento del gráfico. Llama al método IChart.ValidateChartLayout() antes para obtener valores reales.<br/>            Lectura **float**. |
| [`chart`](/slides/python-net/es/aspose.slides.charts/charttitle/chart/) | Devuelve el gráfico padre.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/es/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/charttitle/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/es/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Inicializa TextFrameForOverriding con el texto en el parámetro "text".<br/>            Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)