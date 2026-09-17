---
title: ChartDataPoint class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/chartdatapoint/
---
## Clase ChartDataPoint

Representa un punto de datos de la serie.

El tipo ChartDataPoint expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`x_value`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Solo lectura [`IStringOrDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/size_value/) | Devuelve el valor de tamaño del punto de datos del gráfico.<br/>            Usado con gráficos Treemap y Sunburst. <br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/color_value/) | Devuelve el valor de color del punto de datos del gráfico.<br/>            Usado con gráficos de mapa. <br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Representa los valores de barras de error de la serie en caso de tipo de valor Custom.<br/>            Solo lectura [`IErrorBarsCustomValues`](/slides/python-net/es/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Solo lectura [`IDataLabel`](/slides/python-net/es/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Especifica que las burbujas tienen un efecto 3-D aplicado.<br/>            Lectura/escritura **bool**. |
| [`explosion`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/explosion/) | Especifica la cantidad que el punto de datos debe moverse desde el centro del pastel.<br/>            Lectura/escritura **int**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/format/) | Representa las propiedades de formato.<br/>            Lectura/escritura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/marker/) | Especifica un marcador de datos.<br/>            Solo lectura [`IMarker`](/slides/python-net/es/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/set_as_total/) | Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall. |
| [`related_legend_entry`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Propiedades de la entrada de leyenda correspondiente en caso de que el tipo de gráfico sea de esta lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Solo lectura [`ILegendEntryProperties`](/slides/python-net/es/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/data_point_levels/) | Devuelve el contenedor de niveles de puntos de datos. Aplicado para las series Treeamp y Sunburst.<br/>            La indexación de niveles de puntos de datos comienza en cero. |
| [`index`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Especifica que el punto de datos invertirá sus colores si el valor es negativo.<br/>            Lectura/escritura **bool**. |
| [`actual_x`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/actual_x/) | Especifica la ubicación real x (izquierda) del elemento del gráfico respecto a la esquina superior izquierda del gráfico.<br/>            Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`actual_y`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/actual_y/) | Especifica la parte superior real del elemento del gráfico respecto a la esquina superior izquierda del gráfico.<br/>            Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`actual_width`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/actual_width/) | Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |
| [`actual_height`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/actual_height/) | Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. <br/>            Lectura **float**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`remove(self)`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/remove/#) | Elimina DataPoint de la serie del gráfico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/es/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico.<br/>            Este color se utiliza por defecto si FillType es igual a NotDefined. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)