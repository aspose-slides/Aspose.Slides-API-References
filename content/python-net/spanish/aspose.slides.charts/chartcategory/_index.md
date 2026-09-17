---
title: ChartCategory class
second_title: Aspose.Slides para Python via .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/chartcategory/
---
## ChartCategory clase

Representa categorías de gráfico.

El tipo ChartCategory expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`use_cell`](/slides/python-net/es/aspose.slides.charts/chartcategory/use_cell/) | Si es true entonces la propiedad AsCell está actual. En otras palabras, la hoja de cálculo se usa para <br/>            almacenar la categoría (este caso admite una categoría de varios niveles).<br/>            Si es false entonces la propiedad AsLiteral está actual. En otras palabras, la hoja de cálculo NO se usa <br/>            para almacenar la categoría (y este caso no admite categorías de varios niveles).<br/>            Solo lectura **bool**. |
| [`as_cell`](/slides/python-net/es/aspose.slides.charts/chartcategory/as_cell/) | Devuelve o establece el objeto IChartDataCell.<br/>            Si la categoría es de varios niveles entonces se usa el objeto IChartDataCell para el nivel "0".<br/>            Lectura/escritura [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/es/aspose.slides.charts/chartcategory/as_literal/) | Devuelve o establece el objeto AsLiteral.<br/>            Lectura/escritura **any**. |
| [`value`](/slides/python-net/es/aspose.slides.charts/chartcategory/value/) | Si UseCell es true entonces esta propiedad representa la propiedad AsCell.Value.<br/>            Si UseCell es false entonces esta propiedad representa la propiedad AsLiteral.<br/>            Lectura/escritura **any**. |
| [`grouping_levels`](/slides/python-net/es/aspose.slides.charts/chartcategory/grouping_levels/) | Contenedor administrado de los valores de los niveles de agrupación de la categoría del gráfico.<br/>            La categoría de varios niveles contiene más de un nivel de agrupación.<br/>            La indexación de los niveles de agrupación comienza en cero.<br/>            Solo lectura [`IChartCategoryLevelsManager`](/slides/python-net/es/aspose.slides.charts/ichartcategorylevelsmanager). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`remove(self)`](/slides/python-net/es/aspose.slides.charts/chartcategory/remove/#) | Elimina la categoría del gráfico. |


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)