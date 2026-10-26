---
title: IDataLabelCollection class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelcollection/
---
## Clase IDataLabelCollection

Representa etiquetas de serie.

El tipo IDataLabelCollection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Devuelve el formato predeterminado de todas las etiquetas de datos en la colección.<br/>            Solo lectura [`IDataLabelFormat`](/slides/python-net/es/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Representa el formato de las líneas guía de las etiquetas de datos.<br/>             Solo lectura [`IChartLinesFormat`](/slides/python-net/es/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/is_visible/) | False significa que la etiqueta de datos no es visible de forma predeterminada (y por lo tanto todas las <br/>            banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son false).<br/>            Solo lectura **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Obtiene el número de etiquetas de datos visibles en la colección.<br/>            Solo lectura **int**. |
| [`count`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/count/) | Obtiene el número total de etiquetas de datos en la colección.<br/>            Solo lectura **int**. |
| [`parent_series`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/parent_series/) | Devuelve la serie de gráfico principal.<br/>            Solo lectura [`IChartSeries`](/slides/python-net/es/aspose.slides.charts/ichartseries). |
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
| [`hide(self)`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/hide/#) | Oculta la etiqueta de datos de forma predeterminada estableciendo todas las banderas Show*-flags (ShowValue, ...) de la <br/>            propiedad DefaultDataLabelFormat en estado false.<br/>            IsVisible será false después de esto. |
| [`index_of(self, value)`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Devuelve el índice del DataLabel especificado en la colección. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)