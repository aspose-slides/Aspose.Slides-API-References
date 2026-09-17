---
title: Axis class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/axis/
---
## Axis clase

Encapsula el objeto que representa el eje de un gráfico.

El tipo Axis expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`chart`](/slides/python-net/es/aspose.slides.charts/axis/chart/) | Devuelve el gráfico principal.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/es/aspose.slides.charts/axis/axis_between_categories/) | Indica si el eje de valores cruza el eje de categorías entre categorías.<br/>             Esta propiedad se aplica solo a ejes de categorías y no se aplica a gráficos 3D.<br/>             Lectura/escritura **bool**. |
| [`category_axis_type`](/slides/python-net/es/aspose.slides.charts/axis/category_axis_type/) | Especifica el tipo del eje de categorías.<br/>            Lectura/escritura [`CategoryAxisType`](/slides/python-net/es/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/es/aspose.slides.charts/axis/cross_at/) | Representa el punto en el eje donde el eje perpendicular lo cruza.<br/>             Lectura/escritura **float**. |
| [`display_unit`](/slides/python-net/es/aspose.slides.charts/axis/display_unit/) | Especifica el valor de escala de las unidades de visualización para el eje de valores.<br/>             Lectura/escritura [`DisplayUnitType`](/slides/python-net/es/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/es/aspose.slides.charts/axis/actual_max_value/) | Especifica el valor máximo real en el eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [`actual_min_value`](/slides/python-net/es/aspose.slides.charts/axis/actual_min_value/) | Especifica el valor mínimo real en el eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [`actual_major_unit`](/slides/python-net/es/aspose.slides.charts/axis/actual_major_unit/) | Especifica la unidad mayor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [`actual_minor_unit`](/slides/python-net/es/aspose.slides.charts/axis/actual_minor_unit/) | Especifica la unidad menor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [`actual_major_unit_scale`](/slides/python-net/es/aspose.slides.charts/axis/actual_major_unit_scale/) | Especifica la escala de la unidad mayor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [`actual_minor_unit_scale`](/slides/python-net/es/aspose.slides.charts/axis/actual_minor_unit_scale/) | Especifica la escala de la unidad menor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real. |
| [`is_automatic_max_value`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_max_value/) | Indica si el valor máximo se asigna automáticamente.<br/>             Lectura/escritura **bool**. |
| [`max_value`](/slides/python-net/es/aspose.slides.charts/axis/max_value/) | Representa el valor máximo en el eje de valores.<br/>             Lectura/escritura **float**. |
| [`minor_unit`](/slides/python-net/es/aspose.slides.charts/axis/minor_unit/) | Representa las unidades menores para el eje de fecha o valor.<br/>             Lectura/escritura **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_minor_unit/) | Indica si la unidad menor del eje se asigna automáticamente.<br/>             Lectura/escritura **bool**. |
| [`major_unit`](/slides/python-net/es/aspose.slides.charts/axis/major_unit/) | Representa las unidades mayores para el eje de fecha o valor.<br/>             Lectura/escritura **float**. |
| [`is_automatic_major_unit`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_major_unit/) | Indica si la unidad mayor del eje se asigna automáticamente. <br/>            Lectura/escritura **bool**. |
| [`is_automatic_min_value`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_min_value/) | Indica si el valor mínimo se asigna automáticamente.<br/>             Lectura/escritura **bool**. |
| [`min_value`](/slides/python-net/es/aspose.slides.charts/axis/min_value/) | Representa el valor mínimo en el eje de valores.<br/>             Lectura/escritura **float**. |
| [`is_logarithmic`](/slides/python-net/es/aspose.slides.charts/axis/is_logarithmic/) | Indica si el tipo de escala del eje de valores es logarítmico o no.<br/>             Lectura/escritura **bool**. |
| [`log_base`](/slides/python-net/es/aspose.slides.charts/axis/log_base/) | Representa la base logarítmica. El valor predeterminado es 10.<br/>             Lectura/escritura **float**. |
| [`is_plot_order_reversed`](/slides/python-net/es/aspose.slides.charts/axis/is_plot_order_reversed/) | Indica si MS PowerPoint dibuja los puntos de datos de último a primero.<br/>             Lectura/escritura **bool**. |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/axis/is_visible/) | Indica si el eje es visible.<br/>             Lectura/escritura **bool**. |
| [`major_tick_mark`](/slides/python-net/es/aspose.slides.charts/axis/major_tick_mark/) | Representa el tipo de marca de graduación mayor para el eje especificado.<br/>             Lectura/escritura [`TickMarkType`](/slides/python-net/es/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/es/aspose.slides.charts/axis/minor_tick_mark/) | Representa el tipo de marca de graduación menor para el eje especificado.<br/>             Lectura/escritura [`TickMarkType`](/slides/python-net/es/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/es/aspose.slides.charts/axis/tick_label_position/) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado.<br/>             Lectura/escritura [`TickLabelPositionType`](/slides/python-net/es/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/es/aspose.slides.charts/axis/major_unit_scale/) | Representa la escala de la unidad mayor para el eje de fecha.<br/>             Lectura/escritura [`TimeUnitType`](/slides/python-net/es/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/es/aspose.slides.charts/axis/minor_unit_scale/) | Representa la escala de la unidad mayor para el eje de fecha.<br/>             Lectura/escritura [`TimeUnitType`](/slides/python-net/es/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/es/aspose.slides.charts/axis/base_unit_scale/) | Especifica la unidad de tiempo más pequeña representada en el eje de fecha.<br/>            Lectura/escritura [`TimeUnitType`](/slides/python-net/es/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/es/aspose.slides.charts/axis/minor_grid_lines_format/) | Representa el formato de líneas de cuadrícula menores en un eje de gráfico.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/es/aspose.slides.charts/axis/major_grid_lines_format/) | Representa el formato de líneas de cuadrícula mayores en un eje de gráfico.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/es/aspose.slides.charts/axis/show_minor_grid_lines/) | Para ocultar la línea de cuadrícula menor, establezca MinorGridLinesFormat.Line.FillFormat.FillType en FillType.NoFill.<br/>            Solo lectura **bool**. |
| [`show_major_grid_lines`](/slides/python-net/es/aspose.slides.charts/axis/show_major_grid_lines/) | Para ocultar la línea de cuadrícula mayor, establezca MajorGridLinesFormat.Line.FillFormat.FillType en FillType.NoFill.<br/>            Solo lectura **bool**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/axis/format/) | Representa el formato del eje.<br/>             Solo lectura [`IAxisFormat`](/slides/python-net/es/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/axis/text_format/) | Representa el formato del texto.<br/>             Solo lectura [`IChartTextFormat`](/slides/python-net/es/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/es/aspose.slides.charts/axis/title/) | Obtiene el título del eje.<br/>             Solo lectura [`IChartTitle`](/slides/python-net/es/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/es/aspose.slides.charts/axis/cross_type/) | Representa el CrossType en el eje especificado donde cruza el otro eje.<br/>             Lectura/escritura [`CrossesType`](/slides/python-net/es/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/es/aspose.slides.charts/axis/position/) | Representa la posición del eje.<br/>             Lectura/escritura [`AxisPositionType`](/slides/python-net/es/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/es/aspose.slides.charts/axis/has_title/) | Determina si un eje tiene un título visible.<br/>            Lectura/escritura **bool**. |
| [`number_format`](/slides/python-net/es/aspose.slides.charts/axis/number_format/) | Representa la cadena de formato para las etiquetas del eje.<br/>            Lectura/escritura **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/es/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Indica si el formato está vinculado a los datos de origen.<br/>            Lectura/escritura **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/es/aspose.slides.charts/axis/tick_label_rotation_angle/) | Representa el ángulo de rotación de las etiquetas de graduación.<br/>            Lectura/escritura **float**. |
| [`tick_label_spacing`](/slides/python-net/es/aspose.slides.charts/axis/tick_label_spacing/) | Especifica cuántas etiquetas de graduación se omiten entre las etiquetas que se dibujan. Se aplica a ejes de categoría o de serie.<br/>            Lectura/escritura **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Especifica el valor de espaciado automático de etiquetas de graduación. Si es falso: use la propiedad TickLabelSpacing.<br/>            Lectura/escritura **bool**. |
| [`tick_marks_spacing`](/slides/python-net/es/aspose.slides.charts/axis/tick_marks_spacing/) | Especifica cuántas marcas de graduación se deben omitir antes de que se dibuje la siguiente <br/>            Se aplica a ejes de categoría o de serie.<br/>            Lectura/escritura **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Especifica el valor de espaciado automático de marcas de graduación. Si es falso: use la propiedad TickMarksSpacing.<br/>            Lectura/escritura **bool**. |
| [`label_offset`](/slides/python-net/es/aspose.slides.charts/axis/label_offset/) | Especifica la distancia de las etiquetas al eje. Se aplica a ejes de categoría o de fecha. El valor debe estar entre 0% y 1000%.<br/>            Lectura/escritura **int**. |
| [`aggregation_type`](/slides/python-net/es/aspose.slides.charts/axis/aggregation_type/) | Representa el tipo de agregación del eje de categorías (agrupamiento). Se aplica a categorías. Se usa solo con series Histogram o HistogramPareto. |
| [`bin_width`](/slides/python-net/es/aspose.slides.charts/axis/bin_width/) | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType está establecido a AxisAggregationType.ByBinWidth. <br/>            Se aplica a ejes de categoría. Se usa solo con series Histogram o HistogramPareto. |
| [`number_of_bins`](/slides/python-net/es/aspose.slides.charts/axis/number_of_bins/) | Especifica el número de contenedores cuando el valor de la propiedad AggregationType está establecido a AxisAggregationType.ByNumberOfBins. <br/>            Se aplica a ejes de categoría. Se usa solo con series Histogram o HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/es/aspose.slides.charts/axis/is_overflow_bin/) | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| [`is_automatic_overflow_bin`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Especifica el valor automático del contenedor de desbordamiento. Si es falso: use la propiedad OverflowBin. |
| [`overflow_bin`](/slides/python-net/es/aspose.slides.charts/axis/overflow_bin/) | Especifica el valor personalizado del contenedor de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin está establecida a false y la propiedad IsOverflowBin es verdadera. |
| [`is_underflow_bin`](/slides/python-net/es/aspose.slides.charts/axis/is_underflow_bin/) | Especifica si se aplica el contenedor de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| [`is_automatic_underflow_bin`](/slides/python-net/es/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Especifica el valor automático del contenedor de subdesbordamiento. Si es falso: use la propiedad UnderflowBin. |
| [`underflow_bin`](/slides/python-net/es/aspose.slides.charts/axis/underflow_bin/) | Especifica el valor personalizado del contenedor de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin está establecida a false y la propiedad IsUnderflowBin es verdadera. |
| [`slide`](/slides/python-net/es/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/axis/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/es/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Establece la propiedad IAxis.CategoryAxisType con un valor que se determina automáticamente en función de los datos del eje. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)