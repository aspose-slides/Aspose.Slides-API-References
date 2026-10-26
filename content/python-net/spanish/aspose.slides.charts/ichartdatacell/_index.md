---
title: IChartDataCell class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell clase

Representa una celda para datos de gráfico.

El tipo IChartDataCell expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/row/) | Returns the index of the row of worksheet in which the cell is located.<br/>            Solo lectura **int**. |
| [`column`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/column/) | Returns the index of the column of worksheet in which the cell is located.<br/>            Solo lectura **int**. |
| [`value`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/value/) | Obtiene o establece el valor de una celda.<br/>            Lectura/escritura **any**. |
| [`formula`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/formula/) | Obtiene o establece la fórmula en estilo A1. |
| [`r1c1_formula`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/r1c1_formula/) | Obtiene o establece la fórmula en estilo R1C1. |
| [`chart_data_worksheet`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | Obtiene la hoja de cálculo.<br/>            Solo lectura [`IChartDataWorksheet`](/slides/python-net/es/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/is_hidden/) | Determina si la celda está oculta.<br/>            Solo lectura **bool**. |
| [`custom_number_format`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/custom_number_format/) | Obtiene o establece el formato de visualización personalizado de números y fechas. <br/>            Si el valor está vacío se usará el valor PresetNumberFormat.<br/>            Lectura/escritura **str**. |
| [`preset_number_format`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/preset_number_format/) | Obtiene o establece el formato de visualización incorporado de números y fechas. El número predefinido debe estar en [0..22] o [37..49].<br/>             Lectura/escritura **int**. |

## Métodos

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/es/aspose.slides.charts/ichartdatacell/calculate/#bool) | Si la celda contiene una fórmula, el valor se actualizará en base a esa fórmula. |


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)