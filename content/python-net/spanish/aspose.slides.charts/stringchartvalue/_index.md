---
title: StringChartValue class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/stringchartvalue/
---
## StringChartValue clase

Representa un valor de cadena que puede almacenarse en un documento de presentación pptx de dos maneras:
            1) en celda/celdas del libro de trabajo relacionado con el gráfico;
            2) como valor literal.

**Herencia:**[`StringChartValue`](/slides/python-net/es/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/es/aspose.slides.charts/basechartvalue)

El tipo StringChartValue expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`data_source_type`](/slides/python-net/es/aspose.slides.charts/stringchartvalue/data_source_type/) | Especifica si la propiedad AsCell, AsCells, AsLiteralString o AsLiteralDouble <br/>            está presente en los descendientes. En otras palabras, especifica el tipo <br/>            de valor de la propiedad Data. Lectura/escritura [`DataSourceType`](/slides/python-net/es/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/es/aspose.slides.charts/stringchartvalue/data/) | Devuelve o establece el objeto Data.<br/>            Lectura/escritura **any**. |
| [`as_cells`](/slides/python-net/es/aspose.slides.charts/stringchartvalue/as_cells/) | No se permite asignar un valor nulo.<br/>            El valor devuelto siempre no es None.<br/>            Lectura/escritura [`IChartCellCollection`](/slides/python-net/es/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/es/aspose.slides.charts/stringchartvalue/as_literal_string/) | Devuelve o establece el valor como cadena literal.<br/>            Lectura/escritura **str**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/es/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Establece el valor a partir de la celda especificada. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/es/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Si la propiedad DataSourceType es DataSourceType.Worksheet entonces este método devuelve la dirección<br/>            de las celdas en el libro de trabajo que representan los datos de cadena. En caso contrario devuelve<br/>            una cadena vacía. |

### Ver también
* clase [`BaseChartValue`](/slides/python-net/es/aspose.slides.charts/basechartvalue)
* clase [`StringChartValue`](/slides/python-net/es/aspose.slides.charts/stringchartvalue)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)