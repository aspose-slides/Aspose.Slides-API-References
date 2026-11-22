---
title: IChartSeriesGroup class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup clase

Representa un grupo de series.

El tipo IChartSeriesGroup expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/type/) | Devuelve un tipo de este grupo de series.<br/>            Solo lectura [`CombinableSeriesTypesGroup`](/slides/python-net/es/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indica si las series de este grupo se trazan en el eje secundario.<br/>            Solo lectura **bool**. |
| [`series`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/series/) | Devuelve una colección de solo lectura de series de gráfico.<br/>            Solo lectura [`IChartSeriesReadonlyCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Proporciona acceso a las barras superior/inferior de un gráfico de líneas o de acciones.<br/>            Solo lectura [`IUpDownBarsManager`](/slides/python-net/es/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/gap_width/) | Obtiene o establece el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna.<br/>            El valor debe estar entre 0 y 500.<br/>            Lectura/escritura **int**. |
| [`gap_depth`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador.<br/>            El valor debe estar entre 0 y 500.<br/>            Lectura/escritura **int**. |
| [`first_slice_angle`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Obtiene o establece el ángulo del primer segmento de pastel o rosquilla, <br/>            en grados (en sentido horario desde arriba, de 0 a 360 grados).<br/>            Lectura/escritura **int**. |
| [`is_color_varied`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Especifica que cada marcador de datos en la serie tenga un color diferente.<br/>            Lectura/escritura **bool**. |
| [`has_series_lines`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Verdadero si el gráfico tiene líneas de series. Aplicado a gráficos de barras apiladas y OfPie.<br/>            Lectura/escritura **bool**. |
| [`overlap`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/overlap/) | Especifica cuánto se solapan las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %).<br/>             - -100%: Espaciado máximo (las barras están completamente separadas).<br/>             - 0%: Las barras se colocan una al lado de la otra sin solapamiento ni espacio.<br/>             - 100%: Solapamiento máximo (las barras se superponen completamente).<br/>             Esta propiedad es Lectura/escritura **int**. |
| [`second_pie_size`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Especifica el tamaño del segundo pastel o barra de un gráfico pastel-sobre-pastel o <br/>            un gráfico barra-sobre-pastel, como un porcentaje del tamaño del primer pastel (puede <br/>            estar entre 5 y 200 perc).<br/>            Lectura/escritura **int**. |
| [`pie_split_position`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Especifica un valor que se usará para determinar qué puntos de datos <br/>            están en el segundo pastel o barra en un gráfico pastel-sobre-pastel o barra-sobre-pastel. <br/>            Se usa junto con la propiedad PieSplitBy.<br/>            Lectura/escritura **float**. |
| [`pie_split_by`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra <br/>            en un gráfico pastel-sobre-pastel o barra-sobre-pastel.<br/>            Lectura/escritura [`PieSplitType`](/slides/python-net/es/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | La información de división personalizada para un gráfico pastel-sobre-pastel o barra-sobre-pastel con una división personalizada.<br/>            Contiene puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico pastel-sobre-pastel o <br/>            barra-sobre-pastel.<br/>            Solo lectura [`IPieSplitCustomPointCollection`](/slides/python-net/es/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 perc <br/>            del tamaño del área de trazado).<br/>            Lectura/escritura **int**. |
| [`bubble_size_scale`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Especifica el factor de escala para el gráfico de burbujas (puede estar <br/>            entre 0 y 300 perc del tamaño predeterminado).<br/>            Lectura/escritura **int**. |
| [`hi_low_lines_format`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Especifica el formato de HiLowLines. <br/>            HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas.<br/>            Lectura/escritura [`BubbleSizeRepresentationType`](/slides/python-net/es/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Obtiene el elemento en el índice especificado.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Comentarios

1) Consulte el resumen y los comentarios de la clase ChartSeriesGroupCollection y el enum CombinableSeriesTypesGroup.
            2) El grupo de series contiene algunas propiedades de series que son comunes para 
            cada serie en el grupo ("propiedades del grupo de series").
            Las "propiedades del grupo de series" en la clase ChartSeriesGroup son Lectura/escritura.
            Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries. 


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)