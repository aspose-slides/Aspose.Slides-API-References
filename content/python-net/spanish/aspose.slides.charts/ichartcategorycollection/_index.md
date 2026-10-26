---
title: IChartCategoryCollection class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection clase

Representa una colección de [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory)

El tipo IChartCategoryCollection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`use_cells`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/use_cells/) | Si es true entonces la hoja de cálculo se usa para almacenar categorías (este caso admite categorías de varios niveles).<br/>            Si es false entonces la hoja de cálculo NO se usa para almacenar valores (y este caso no admite <br/>            categorías de varios niveles).<br/>            Lectura/escritura **bool**. |
| [`grouping_level_count`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Devuelve el recuento de niveles de agrupación de categorías utilizados.<br/>            Es más de uno para categorías de varios niveles.<br/>            Solo lectura **int**. |

Obtiene el elemento en el índice especificado.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Si la categoría existe en la colección, la devuelve. De lo contrario crea una nueva categoría de gráfico a partir de <br/>            [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) y la agrega a la colección. |
| [`add(self, value)`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/add/#any) | Crea un nuevo [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory) a partir del valor y lo agrega a la colección. |
| [`index_of(self, value)`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Busca el [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory) especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la Colección |
| [`remove(self, value)`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Elimina el valor especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Elimina el elemento en el índice dado. |
| [`clear(self)`](/slides/python-net/es/aspose.slides.charts/ichartcategorycollection/clear/#) | Elimina todos los elementos de la colección. |

### Ver también
* clase [`IChartCategory`](/slides/python-net/es/aspose.slides.charts/ichartcategory)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)