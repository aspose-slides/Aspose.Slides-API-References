---
title: IChartCategory class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartcategory/
---
## IChartCategory clase

Representa categorías de gráfico.

El tipo IChartCategory expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`use_cell`](/slides/python-net/es/aspose.slides.charts/ichartcategory/use_cell/) | Si es verdadero entonces la propiedad AsCell es la actual. En otras palabras, la hoja de cálculo se utiliza para <br/>            almacenar la categoría (este caso admite una categoría multinivel).<br/>            Si es falso entonces la propiedad AsLiteral es la actual. En otras palabras, la hoja de cálculo NO se utiliza <br/>            para almacenar la categoría (y este caso no admite categorías multinivel).<br/>            Solo lectura **bool**. |
| [`as_cell`](/slides/python-net/es/aspose.slides.charts/ichartcategory/as_cell/) | Devuelve o establece el objeto IChartDataCell.<br/>            Si la categoría es multinivel entonces se usa el objeto IChartDataCell para el nivel "0".<br/>            Lectura/escritura [`IChartDataCell`](/slides/python-net/es/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/es/aspose.slides.charts/ichartcategory/as_literal/) | Devuelve o establece AsLiteral si UseCell es falso.<br/>            Lectura/escritura **any**. |
| [`value`](/slides/python-net/es/aspose.slides.charts/ichartcategory/value/) | Si UseCell es verdadero entonces esta propiedad representa la propiedad AsCell.Value.<br/>            Si UseCell es falso entonces esta propiedad representa la propiedad AsLiteral.<br/>            Lectura/escritura **any**. |
| [`grouping_levels`](/slides/python-net/es/aspose.slides.charts/ichartcategory/grouping_levels/) | Contenedor gestionado de los valores de los niveles de agrupación de la categoría del gráfico.<br/>            La categoría multinivel contiene más de un nivel de agrupación.<br/>            La indexación de los niveles de agrupación es basada en cero.<br/>            Solo lectura [`IChartCategoryLevelsManager`](/slides/python-net/es/aspose.slides.charts/ichartcategorylevelsmanager). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`remove(self)`](/slides/python-net/es/aspose.slides.charts/ichartcategory/remove/#) | Elimina la categoría del gráfico. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)