---
title: ChartSeriesGroup class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup clase

Representa un grupo de series.

El tipo ChartSeriesGroup expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/type/) | Devuelve un tipo de este grupo de series.<br/>            Solo lectura [`CombinableSeriesTypesGroup`](/slides/python-net/es/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indica si las series de este grupo se trazan en el eje secundario.<br/>            Solo lectura **bool**. |
| [`series`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/series/) | Devuelve una colección de series.<br/>            Solo lectura [`IChartSeriesReadonlyCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Proporciona acceso a las barras arriba/abajo de un gráfico de línea o de bolsa.<br/>            Solo lectura [`IUpDownBarsManager`](/slides/python-net/es/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/gap_width/) | Obtiene o establece el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna.<br/>            El valor debe estar entre 0 y 500.<br/>            Lectura/escritura **int**. |
| [`gap_depth`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/gap_depth/) | Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador.<br/>            El valor debe estar entre 0 y 500.<br/>            Lectura/escritura **int**. |
| [`first_slice_angle`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Obtiene o establece el ángulo de la primera porción de pastel o rosquilla, <br/>            en grados (en sentido horario desde arriba, de 0 a 360 grados).<br/>            Lectura/escritura **int**. |
| [`doughnut_hole_size`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 0 y 90 por ciento <br/>            del tamaño del área de trazado).<br/>            Lectura/escritura **int**. |
| [`overlap`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/overlap/) | Especifica cuánto se superpondrán las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%).<br/>             - -100%: Espaciado máximo (las barras están completamente separadas).<br/>             - 0%: Las barras se colocan una al lado de la otra sin superposición ni espacio.<br/>             - 100%: Superposición máxima (las barras se superponen completamente entre sí).<br/>             Esta propiedad es lectura/escritura **int**. |
| [`second_pie_size`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Especifica el tamaño del segundo pastel o barra de un gráfico pastel-sobre-pastel o <br/>            un gráfico barra-sobre-pastel, como un porcentaje del tamaño del primer pastel (puede <br/>            estar entre 5 y 200 por ciento).<br/>            Lectura/escritura **int**. |
| [`bubble_size_representation`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas.<br/>            Lectura/escritura [`BubbleSizeRepresentationType`](/slides/python-net/es/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Especifica un valor que se usará para determinar qué puntos de datos <br/>            están en el segundo pastel o barra en un gráfico pastel-sobre-pastel o barra-sobre-pastel. <br/>            Se usa junto con la propiedad PieSplitBy.<br/>            Lectura/escritura **float**. |
| [`pie_split_by`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra <br/>            en un gráfico pastel-sobre-pastel o barra-sobre-pastel.<br/>            Lectura/escritura [`PieSplitType`](/slides/python-net/es/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Especifica que cada marcador de datos en la serie tiene un color diferente.<br/>            Lectura/escritura **bool**. |
| [`has_series_lines`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie.<br/>            Lectura/escritura **bool**. |
| [`hi_low_lines_format`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Especifica el formato HiLowLines. <br/>            HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Especifica el factor de escala para el gráfico de burbujas (puede estar <br/>            entre 0 y 300 por ciento del tamaño predeterminado).<br/>            Lectura/escritura **int**. |
| [`pie_split_custom_points`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | La información de división personalizada para un gráfico pastel-sobre-pastel o barra-sobre-pastel con una división personalizada.<br/>            Contiene puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico pastel-sobre-pastel o <br/>            barra-sobre-pastel.<br/>            Solo lectura [`PieSplitCustomPointCollection`](/slides/python-net/es/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/chart/) | Devuelve el gráfico padre.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Obtiene el elemento en el índice especificado.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Observaciones

1) Consulte el resumen y los comentarios de la clase ChartSeriesGroupCollection y del enum CombinableSeriesTypesGroup.
            2) El grupo de series contiene algunas propiedades de series que son comunes para 
            cada serie en el grupo ("propiedades del grupo de series").
            "Propiedades del grupo de series" en la clase ChartSeriesGroup es lectura/escritura.
            Cada una de las "propiedades del grupo de series" puede tener una proyección solo lectura en la clase ChartSeries.


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)