---
title: ChartDataCell class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.charts/chartdatacell/
---
## ChartDataCell clase

Representa una celda para datos de gráfico.

El tipo ChartDataCell expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`row`](/slides/python-net/es/aspose.slides.charts/chartdatacell/row/) | Devuelve el índice de la fila de la hoja de cálculo en la que se encuentra la celda.<br/>            Solo lectura **int**. |
| [`column`](/slides/python-net/es/aspose.slides.charts/chartdatacell/column/) | Devuelve el índice de la columna de la hoja de cálculo en la que se encuentra la celda.<br/>            Solo lectura **int**. |
| [`value`](/slides/python-net/es/aspose.slides.charts/chartdatacell/value/) | Obtiene o establece el valor de una celda.<br/>            Lectura/escritura **any**. |
| [`formula`](/slides/python-net/es/aspose.slides.charts/chartdatacell/formula/) | Obtiene o establece la fórmula en estilo A1. |
| [`r1c1_formula`](/slides/python-net/es/aspose.slides.charts/chartdatacell/r1c1_formula/) | Obtiene o establece la fórmula en estilo R1C1. |
| [`chart_data_worksheet`](/slides/python-net/es/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | Obtiene la hoja de cálculo.<br/>            Solo lectura [`IChartDataWorksheet`](/slides/python-net/es/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/es/aspose.slides.charts/chartdatacell/is_hidden/) | Determina si la celda está oculta.<br/>            Solo lectura **bool**. |
| [`custom_number_format`](/slides/python-net/es/aspose.slides.charts/chartdatacell/custom_number_format/) | Obtiene o establece el formato de visualización personalizado de números y fechas.<br/>            Si el valor está vacío se usará el valor PresetNumberFormat.<br/>            Lectura/escritura **str**. |
| [`preset_number_format`](/slides/python-net/es/aspose.slides.charts/chartdatacell/preset_number_format/) | Obtiene o establece el formato de visualización incorporado de números y fechas. El número preestablecido debe estar en [0..22] o [37..49].<br/>            Lectura/escritura **int**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/es/aspose.slides.charts/chartdatacell/calculate/#bool) | Si la celda contiene una fórmula, el valor se actualizará en función de esa fórmula. |

### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)