---
title: IStringChartValue class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue clase

Representa un valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras:
            1) en celda/celdas del libro de trabajo relacionado con el gráfico;
            2) como valor literal.

El tipo IStringChartValue expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`as_literal_string`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/as_literal_string/) | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals.<br/>            Lectura/escritura **str**. |
| [`as_cells`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/data/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`to_string(self)`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/to_string/#) | Devuelve la representación de cadena. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Establece el valor a partir de la celda especificada. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/es/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Si la propiedad DataSourceType es DataSourceType.Worksheet entonces este método devuelve la dirección<br/>            de las celdas en el libro de trabajo que representan los datos de cadena. De lo contrario devuelve<br/>            una cadena vacía. |

### Véase también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)