---
title: DataLabel class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabel/
---
## Clase DataLabel

Representa etiquetas de series.

El tipo DataLabel expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/es/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Crea una nueva instancia de la clase DataLabel. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`chart`](/slides/python-net/es/aspose.slides.charts/datalabel/chart/) | Devuelve el gráfico principal.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/datalabel/is_visible/) | False significa que la etiqueta de datos no es visible (y, por lo tanto, todas las banderas Show*-flags (ShowValue, ...) son falsas).<br/>            Solo lectura **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/es/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Puede contener un texto con formato enriquecido. Si esta propiedad no es None entonces este <br/>            valor de texto con formato sobrescribe el texto autogenerado de la etiqueta de datos.<br/>            El texto autogenerado de la etiqueta de datos significa el texto gestionado por las propiedades ShowSeriesName, <br/>            ShowValue, ... y formateado con la propiedad TextFormatManager.TextFormat.<br/>            Solo lectura [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/datalabel/text_format/) | Devuelve el formato de texto.<br/>            Solo lectura [`IChartTextFormat`](/slides/python-net/es/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/es/aspose.slides.charts/datalabel/x/) | Devuelve o establece la coordenada x de un título como una fracción del ancho del gráfico.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides.charts/datalabel/y/) | Devuelve o establece la coordenada y de un título como una fracción de la altura del gráfico.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides.charts/datalabel/width/) | Devuelve o establece el ancho de un título como una fracción del ancho del gráfico.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides.charts/datalabel/height/) | Devuelve o establece la altura de un título como una fracción de la altura del gráfico.<br/>            Lectura/escritura **float**. |
| [`right`](/slides/python-net/es/aspose.slides.charts/datalabel/right/) | Derecha.<br/>            Solo lectura **float**. |
| [`bottom`](/slides/python-net/es/aspose.slides.charts/datalabel/bottom/) | Abajo.<br/>            Solo lectura **float**. |
| [`data_label_format`](/slides/python-net/es/aspose.slides.charts/datalabel/data_label_format/) | Devuelve el formato de la etiqueta de datos.<br/>            Solo lectura [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/es/aspose.slides.charts/datalabel/value_from_cell/) | Obtiene o establece la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true. |
| [`actual_x`](/slides/python-net/es/aspose.slides.charts/datalabel/actual_x/) | Especifica la ubicación real x (izquierda) del elemento del gráfico en relación con la esquina superior izquierda del gráfico.<br/>            Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`actual_y`](/slides/python-net/es/aspose.slides.charts/datalabel/actual_y/) | Especifica la parte superior real del elemento del gráfico en relación con la esquina superior izquierda del gráfico.<br/>            Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`actual_width`](/slides/python-net/es/aspose.slides.charts/datalabel/actual_width/) | Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`actual_height`](/slides/python-net/es/aspose.slides.charts/datalabel/actual_height/) | Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`slide`](/slides/python-net/es/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/datalabel/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`hide(self)`](/slides/python-net/es/aspose.slides.charts/datalabel/hide/#) | Oculta la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) al estado falso.<br/>            IsVisible será false después de esto. |
| [`get_actual_label_text(self)`](/slides/python-net/es/aspose.slides.charts/datalabel/get_actual_label_text/#) | Devuelve el texto real de la etiqueta basado en la configuración DataLabelFormat o en el valor TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/es/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicializa TextFrameForOverriding con el texto en el parámetro "text".<br/>            Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |

### Véase también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)