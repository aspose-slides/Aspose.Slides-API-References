---
title: ChartCategoryCollection class
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection clase

Representa una colección de [`ChartCategory`](/slides/python-net/es/aspose.slides.charts/chartcategory)

El tipo ChartCategoryCollection expone los siguientes miembros:

## Propiedades

| Property | Descripción |
| :- | :- |
| [`use_cells`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/use_cells/) | Si es true entonces la hoja de cálculo se usa para almacenar categorías (este caso admite categorías de varios niveles).<br/>            Si es false entonces la hoja de cálculo NO se usa para almacenar valores (y este caso no admite categorías de varios niveles).<br/>            Lectura/escritura **bool**. |
| [`grouping_level_count`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Devuelve el recuento de niveles de agrupación de categorías usados.<br/>            Es mayor que uno para categorías de varios niveles.<br/>            Solo lectura **int**. |

Obtiene el elemento en el índice especificado.

## Indexador

| Name | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Métodos

| Method | Descripción |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Si la categoría existe en la colección, la devuelve. De lo contrario crea una nueva categoría de gráfico a partir de [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell) y la agrega a la colección. |
| [`add(self, value)`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/add/#any) | Crea un nuevo [`ChartCategory`](/slides/python-net/es/aspose.slides.charts/chartcategory) a partir del valor y lo agrega a la colección. |
| [`index_of(self, value)`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Busca el [`ChartCategory`](/slides/python-net/es/aspose.slides.charts/chartcategory) especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la colección. |
| [`remove(self, value)`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Elimina el valor especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Elimina el elemento en el índice dado. |
| [`clear(self)`](/slides/python-net/es/aspose.slides.charts/chartcategorycollection/clear/#) | Elimina todos los elementos de la colección. |

### Ver también
* clase [`ChartCategory`](/slides/python-net/es/aspose.slides.charts/chartcategory)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)