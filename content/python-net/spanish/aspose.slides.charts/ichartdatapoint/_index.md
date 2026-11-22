---
title: IChartDataPoint class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint clase

Representa un punto de datos de la serie.

El tipo IChartDataPoint expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/x_value/) | Obtiene el valor x de un punto de datos del gráfico.<br/>            Solo lectura [`IStringOrDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/y_value/) | Obtiene el valor y de un punto de datos del gráfico.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/bubble_size/) | Obtiene el tamaño de burbuja de un punto de datos del gráfico.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/value/) | Obtiene el valor de un punto de datos del gráfico.<br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Obtiene el valor X en caché de un punto de datos del gráfico.<br/>            Solo lectura [`ICachedChartValue`](/slides/python-net/es/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Obtiene el valor Y en caché de un punto de datos del gráfico.<br/>            Solo lectura [`ICachedChartValue`](/slides/python-net/es/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/cached_value/) | Obtiene el valor en caché de un punto de datos del gráfico.<br/>            Solo lectura [`ICachedChartValue`](/slides/python-net/es/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Obtiene el tamaño de burbuja en caché de un punto de datos del gráfico.<br/>            Solo lectura [`ICachedChartValue`](/slides/python-net/es/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/size_value/) | Obtiene el valor de tamaño de un punto de datos del gráfico.<br/>            Usado con gráficos Treemap y Sunburst. <br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/color_value/) | Obtiene el valor de color de un punto de datos del gráfico.<br/>            Usado con gráficos de mapa. <br/>            Solo lectura [`IDoubleChartValue`](/slides/python-net/es/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Representa los valores de barras de error de la serie en caso de tipo de valor Custom.<br/>            Solo lectura [`IErrorBarsCustomValues`](/slides/python-net/es/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/label/) | Representa la etiqueta del punto de datos del gráfico.<br/>            Solo lectura [`IDataLabel`](/slides/python-net/es/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Especifica que las burbujas tengan un efecto 3-D aplicado.<br/>            Lectura/escritura **bool**. |
| [`explosion`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/explosion/) | Especifica la cantidad que el punto de datos se moverá desde el centro del pastel.<br/>            Lectura/escritura **int**. |
| [`format`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/format/) | Representa las propiedades de formato.<br/>            Lectura/escritura [`IFormat`](/slides/python-net/es/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/marker/) | Especifica un marcador de datos.<br/>            Solo lectura [`IMarker`](/slides/python-net/es/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Propiedades de la entrada de leyenda correspondiente en caso de que el tipo de gráfico sea de esta lista:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Solo lectura [`ILegendEntryProperties`](/slides/python-net/es/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/set_as_total/) | Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall. |
| [`invert_if_negative`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Especifica que el punto de datos invertirá sus colores si el valor es negativo.<br/>            Lectura/escritura **bool**. |
| [`data_point_levels`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Devuelve el contenedor de niveles del punto de datos. Aplicado para series Treeamp y Sunburst.<br/>            El indexado de los niveles del punto de datos comienza en cero. |
| [`index`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/index/) | Determina a cuál de las colecciones de hijos del padre se aplica este punto de datos.<br/>            Lectura **int**. |
| [`actual_x`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/remove/#) | Elimina DataPoint de la serie del gráfico. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/es/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico.<br/>            Este color se usa por defecto si FillType es igual a NotDefined. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)