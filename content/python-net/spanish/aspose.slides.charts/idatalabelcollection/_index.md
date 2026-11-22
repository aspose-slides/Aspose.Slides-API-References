---
title: IDataLabelCollection class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection clase

Representa las etiquetas de la serie.

El tipo IDataLabelCollection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Devuelve el formato predeterminado de todas las etiquetas de datos en la colección.<br/>            Solo lectura [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Representa el formato de las líneas guías de las etiquetas de datos.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/is_visible/) | Falso significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las <br/>            banderas Show* (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas).<br/>            Solo lectura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Obtiene el número de etiquetas de datos visibles en la colección.<br/>            Solo lectura **int**. |
| [`count`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/count/) | Obtiene el número de todas las etiquetas de datos en la colección.<br/>            Solo lectura **int**. |
| [`parent_series`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/parent_series/) | Devuelve la serie de gráfico principal.<br/>            Solo lectura [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Obtiene o establece el tipo de forma predeterminado para las etiquetas de datos.<br/>             Devuelve [`ShapeType.NOT_DEFINED`](/slides/python-net/es/aspose.slides/shapetype/NOT_DEFINED) si no se define una forma. |
| [`chart`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Obtiene la etiqueta de datos para el punto de datos con el índice especificado.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`hide(self)`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/hide/#) | Hacer que la etiqueta de datos esté oculta por defecto estableciendo todas las banderas Show* (ShowValue, ...) de la propiedad DefaultDataLabelFormat a estado falso.<br/>            IsVisible será falso después de esto. |
| [`index_of(self, value)`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Devuelve un índice del DataLabel especificado en la colección. |


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)