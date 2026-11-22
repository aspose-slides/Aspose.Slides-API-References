---
title: DataLabelCollection class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection clase

Representa etiquetas de una serie.

El tipo DataLabelCollection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`chart`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/chart/) | Devuelve el gráfico padre.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/is_visible/) | False significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son false).<br/>            Solo lectura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Obtiene el número de etiquetas de datos visibles en la colección.<br/>            Solo lectura **int**. |
| [`count`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/count/) | Obtiene el número total de etiquetas de datos en la colección.<br/>            Solo lectura **int**. |
| [`default_data_label_format`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Obtiene el formato predeterminado de la etiqueta de datos.<br/>            Solo lectura [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Representa el formato de las líneas guía de las etiquetas de datos.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/parent_series/) | Obtiene la serie padre.<br/>            Solo lectura [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Obtiene o establece el tipo de forma predeterminado para las etiquetas de datos.<br/>             Devuelve [`ShapeType.NOT_DEFINED`](/slides/python-net/es/aspose.slides/shapetype/NOT_DEFINED) si no se define una forma. |
| [`slide`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/presentation/) |  |

Obtiene la etiqueta de datos para el punto de datos con el índice especificado.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`hide(self)`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/hide/#) | Oculta la etiqueta de datos de forma predeterminada estableciendo todas las banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado false.<br/>            IsVisible será false después de esto. |
| [`index_of(self, value)`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Devuelve un índice del DataLabel especificado en la colección. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)