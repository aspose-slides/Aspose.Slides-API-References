---
title: IChartDataPoint class
second_title: Referencia de API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint clase

Representa un punto de datos de serie.

El tipo IChartDataPoint expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`x_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/x_value/) | Devuelve el valor x del punto de datos del gráfico.<br/>            Solo lectura [`IStringOrDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/y_value/) | Devuelve el valor y del punto de datos del gráfico.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/bubble_size/) | Devuelve el tamaño de la burbuja del punto de datos del gráfico.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/value/) | Devuelve el valor del punto de datos del gráfico.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/size_value/) | Devuelve el valor de tamaño del punto de datos del gráfico.<br/>            Usado con gráficos Treemap y Sunburst.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/color_value/) | Devuelve el valor de color del punto de datos del gráfico.<br/>            Usado con gráficos de mapa.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Representa los valores de barras de error de la serie en caso de tipo de valor Custom.<br/>            Solo lectura [`IErrorBarsCustomValues`](/slides/python-net/es/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/label/) | Representa la etiqueta del punto de datos del gráfico.<br/>            Solo lectura [`IDataLabel`](/slides/python-net/es/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Especifica que las burbujas tienen un efecto 3-D aplicado.<br/>            Lectura/escritura **bool**. |
| [`explosion`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/explosion/) | Especifica la cantidad que el punto de datos debe desplazarse desde el centro del pastel.<br/>            Lectura/escritura **int**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/format/) | Representa las propiedades de formato.<br/>            Lectura/escritura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/marker/) | Especifica un marcador de datos.<br/>            Solo lectura [`IMarker`](/slides/python-net/es/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Propiedades de la entrada de leyenda correspondiente en caso de tipo de gráfico de esta lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Solo lectura [`ILegendEntryProperties`](/slides/python-net/es/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/set_as_total/) | Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall. |
| [`invert_if_negative`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Especifica que el punto de datos invertirá sus colores si el valor es negativo.<br/>            Lectura/escritura **bool**. |
| [`data_point_levels`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Devuelve el contenedor de los niveles del punto de datos. Aplicado a series Treeamp y Sunburst.<br/>            El índice de los niveles del punto de datos comienza en cero. |
| [`index`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/index/) | Determina a cuál de las colecciones de hijos del padre se aplica este punto de datos.<br/>            Lectura **int**. |
| [`actual_x`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`remove(self)`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/remove/#) | Elimina el DataPoint de la serie del gráfico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico.<br/>            Este color se usa por defecto si FillType es NotDefined. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)