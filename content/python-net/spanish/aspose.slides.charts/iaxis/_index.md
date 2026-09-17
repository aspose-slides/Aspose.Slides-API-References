---
title: IAxis class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/iaxis/
---
## IAxis clase

Encapsula el objeto que representa el eje de un gráfico.

El tipo IAxis expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/es/aspose.slides.charts/iaxis/axis_between_categories/) | Representa si el eje de valores cruza el eje de categorías entre categorías.<br/>            Esta propiedad se aplica solo a los ejes de categorías, y no se aplica a los gráficos 3D.<br/>            Lectura/escritura **bool**. |
| [`cross_at`](/slides/python-net/es/aspose.slides.charts/iaxis/cross_at/) | Representa el punto en el eje donde el eje perpendicular lo cruza.<br/>            Lectura/escritura **float**. |
| [`display_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/display_unit/) | Especifica el valor de escala de las unidades de visualización para el eje de valores.<br/>            Lectura/escritura [`DisplayUnitType`](/slides/python-net/es/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/es/aspose.slides.charts/iaxis/actual_max_value/) | Especifica el valor máximo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [`actual_min_value`](/slides/python-net/es/aspose.slides.charts/iaxis/actual_min_value/) | Especifica el valor mínimo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [`actual_major_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/actual_major_unit/) | Especifica la unidad mayor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [`actual_minor_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/actual_minor_unit/) | Especifica la unidad menor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [`actual_major_unit_scale`](/slides/python-net/es/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Especifica la escala de unidad mayor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [`actual_minor_unit_scale`](/slides/python-net/es/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Especifica la escala de unidad menor real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real. |
| [`is_automatic_max_value`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indica si el valor máximo se asigna automáticamente.<br/>             Lectura/escritura **bool**. |
| [`max_value`](/slides/python-net/es/aspose.slides.charts/iaxis/max_value/) | Representa el valor máximo en el eje de valores.<br/>             Lectura/escritura **float**. |
| [`minor_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/minor_unit/) | Representa las unidades menores para el eje de fechas o valores.<br/>             Lectura/escritura **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indica si la unidad menor del eje se asigna automáticamente.<br/>             Lectura/escritura **bool**. |
| [`major_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/major_unit/) | Representa las unidades mayores para el eje de fechas o valores.<br/>             Lectura/escritura **float**. |
| [`is_automatic_major_unit`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indica si la unidad mayor del eje se asigna automáticamente.<br/>            Lectura/escritura **bool**. |
| [`is_automatic_min_value`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indica si el valor mínimo se asigna automáticamente.<br/>             Lectura/escritura **bool**. |
| [`min_value`](/slides/python-net/es/aspose.slides.charts/iaxis/min_value/) | Representa el valor mínimo en el eje de valores.<br/>             Lectura/escritura **float**. |
| [`is_logarithmic`](/slides/python-net/es/aspose.slides.charts/iaxis/is_logarithmic/) | Representa si el tipo de escala del eje de valores es logarítmico o no.<br/>             Lectura/escritura **bool**. |
| [`log_base`](/slides/python-net/es/aspose.slides.charts/iaxis/log_base/) | Representa la base logarítmica. El valor predeterminado es 10.<br/>             Lectura/escritura **float**. |
| [`is_plot_order_reversed`](/slides/python-net/es/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Representa si MS PowerPoint traza los puntos de datos de último a primero.<br/>             Lectura/escritura **bool**. |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/iaxis/is_visible/) | Representa si el eje es visible.<br/>             Lectura/escritura **bool**. |
| [`major_tick_mark`](/slides/python-net/es/aspose.slides.charts/iaxis/major_tick_mark/) | Representa el tipo de marca de graduación mayor para el eje especificado.<br/>             Lectura/escritura [`TickMarkType`](/slides/python-net/es/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/es/aspose.slides.charts/iaxis/minor_tick_mark/) | Representa el tipo de marca de graduación menor para el eje especificado.<br/>             Lectura/escritura [`TickMarkType`](/slides/python-net/es/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/es/aspose.slides.charts/iaxis/tick_label_position/) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado.<br/>             Lectura/escritura [`TickLabelPositionType`](/slides/python-net/es/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/es/aspose.slides.charts/iaxis/major_unit_scale/) | Representa la escala de unidad mayor para el eje de fechas.<br/>             Lectura/escritura [`TimeUnitType`](/slides/python-net/es/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/es/aspose.slides.charts/iaxis/minor_unit_scale/) | Representa la escala de unidad mayor para el eje de fechas.<br/>             Lectura/escritura [`TimeUnitType`](/slides/python-net/es/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/es/aspose.slides.charts/iaxis/base_unit_scale/) | Especifica la unidad de tiempo más pequeña que se representa en el eje de fechas.<br/>            Lectura/escritura [`TimeUnitType`](/slides/python-net/es/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/es/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Representa el formato de líneas de cuadrícula menores en un eje de gráfico.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/es/aspose.slides.charts/iaxis/major_grid_lines_format/) | Representa el formato de líneas de cuadrícula mayores en un eje de gráfico.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/es/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Representa si se mostraron las líneas de cuadrícula menores.<br/>             Solo lectura **bool**. |
| [`show_major_grid_lines`](/slides/python-net/es/aspose.slides.charts/iaxis/show_major_grid_lines/) | Representa si se mostraron las líneas de cuadrícula mayores.<br/>             Solo lectura **bool**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/iaxis/format/) | Representa el formato del eje.<br/>             Solo lectura [`IAxisFormat`](/slides/python-net/es/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/es/aspose.slides.charts/iaxis/title/) | Obtiene el título del eje.<br/>             Solo lectura [`IChartTitle`](/slides/python-net/es/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/es/aspose.slides.charts/iaxis/cross_type/) | Representa el CrossType en el eje especificado donde cruza el otro eje.<br/>             Lectura/escritura [`CrossesType`](/slides/python-net/es/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/es/aspose.slides.charts/iaxis/position/) | Representa la posición del eje.<br/>             Lectura/escritura [`AxisPositionType`](/slides/python-net/es/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/es/aspose.slides.charts/iaxis/has_title/) | Determina si un eje tiene un título visible.<br/>            Lectura/escritura **bool**. |
| [`number_format`](/slides/python-net/es/aspose.slides.charts/iaxis/number_format/) | Representa la cadena de formato para las etiquetas del eje.<br/>            Lectura/escritura **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/es/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Indica si el formato está vinculado a datos de origen.<br/>            Lectura/escritura **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/es/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Representa el ángulo de rotación de las etiquetas de marcas<br/>            Lectura/escritura **float**. |
| [`tick_label_spacing`](/slides/python-net/es/aspose.slides.charts/iaxis/tick_label_spacing/) | Especifica cuántas etiquetas de marcas se omiten entre las que se dibujan.<br/>            Lectura/escritura **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Especifica si el espaciado automático de etiquetas de marcas está activo. Si es false: use la propiedad TickLabelSpacing.<br/>            Lectura/escritura **bool**. |
| [`tick_marks_spacing`](/slides/python-net/es/aspose.slides.charts/iaxis/tick_marks_spacing/) | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente.<br/>            Aplicado a ejes de categoría o de serie.<br/>            Lectura/escritura **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Especifica si el espaciado automático de marcas de graduación está activo. Si es false: use la propiedad TickMarksSpacing.<br/>            Lectura/escritura **bool**. |
| [`label_offset`](/slides/python-net/es/aspose.slides.charts/iaxis/label_offset/) | Especifica la distancia de las etiquetas desde el eje. Aplicado a ejes de categoría o fecha. El valor debe estar entre 0% y 1000%.<br/>            Lectura/escritura **int**. |
| [`category_axis_type`](/slides/python-net/es/aspose.slides.charts/iaxis/category_axis_type/) | Especifica el tipo del eje de categoría.<br/>            Lectura/escritura [`IAxis.category_axis_type`](/slides/python-net/es/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/es/aspose.slides.charts/iaxis/aggregation_type/) | Representa el tipo de agregación del eje de categoría (agrupación). Aplicado a categoría. Usado solo con series Histogram o HistogramPareto. |
| [`bin_width`](/slides/python-net/es/aspose.slides.charts/iaxis/bin_width/) | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece a AxisAggregationType.ByBinWidth.<br/>            Aplicado a ejes de categoría. Usado solo con series Histogram o HistogramPareto. |
| [`number_of_bins`](/slides/python-net/es/aspose.slides.charts/iaxis/number_of_bins/) | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece a AxisAggregationType.ByNumberOfBins.<br/>            Aplicado a ejes de categoría. Usado solo con series Histogram o HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/es/aspose.slides.charts/iaxis/is_overflow_bin/) | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| [`is_automatic_overflow_bin`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Especifica el valor automático del contenedor de desbordamiento. Si es false: use la propiedad OverflowBin. |
| [`overflow_bin`](/slides/python-net/es/aspose.slides.charts/iaxis/overflow_bin/) | Especifica el valor personalizado del contenedor de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin está establecida a false y la propiedad IsOverflowBin es true. |
| [`is_underflow_bin`](/slides/python-net/es/aspose.slides.charts/iaxis/is_underflow_bin/) | Especifica si se aplica el contenedor de subflujo. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subflujo. |
| [`is_automatic_underflow_bin`](/slides/python-net/es/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Especifica el valor automático del contenedor de subflujo. Si es false: use la propiedad UnderflowBin. |
| [`underflow_bin`](/slides/python-net/es/aspose.slides.charts/iaxis/underflow_bin/) | Especifica el valor personalizado del contenedor de subflujo. Aplicado cuando la propiedad IsAutomaticUnderflowBin está establecida a false y la propiedad IsUnderflowBin es true. |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/es/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/es/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/iaxis/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/es/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Establece la propiedad IAxis.CategoryAxisType con un valor que se determina automáticamente en función de los datos del eje. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)