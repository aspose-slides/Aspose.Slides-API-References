---
title: DataLabelCollection class
second_title: Referencia de la API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection clase

Representa las etiquetas de una serie.

The DataLabelCollection type exposes the following members:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`chart`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/chart/) | Devuelve el gráfico padre.<br/>            Solo lectura [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/is_visible/) | False significa que la etiqueta de datos no es visible por defecto (and so all <br/>            Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son false).<br/>            Solo lectura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Obtiene el número de etiquetas de datos visibles en la colección.<br/>            Solo lectura **int**. |
| [`count`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/count/) | Obtiene el número total de etiquetas de datos en la colección.<br/>            Solo lectura **int**. |
| [`default_data_label_format`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Obtiene el formato predeterminado de la etiqueta de datos.<br/>            Solo lectura [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Representa el formato de líneas guía de las etiquetas de datos.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/parent_series/) | Obtiene la serie padre.<br/>            Solo lectura [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries). |
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
| [`hide(self)`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/hide/#) | Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show*- (ShowValue, ...) de la propiedad DefaultDataLabelFormat al estado false.<br/>            IsVisible será false después de esto. |
| [`index_of(self, value)`](/slides/python-net/es/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Devuelve un índice de la DataLabel especificada en la colección. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)