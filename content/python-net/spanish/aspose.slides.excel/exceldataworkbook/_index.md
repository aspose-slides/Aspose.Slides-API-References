---
title: ExcelDataWorkbook class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook clase

Representa un libro de trabajo que proporciona acceso a datos de Excel para uso general.

El tipo ExcelDataWorkbook expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/__init__/#str) | Inicializa una nueva instancia usando la ruta de archivo especificada. |
| [`__init__(self, stream)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Inicializa una nueva instancia de la clase usando el flujo proporcionado. |

## Métodos

| Method | Descripción |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Obtiene una celda de la hoja de cálculo especificada usando su índice y coordenadas de celda. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Obtiene una celda de la hoja de cálculo especificada usando su nombre y coordenadas de celda. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Obtiene una celda de la hoja de cálculo especificada usando su índice y nombre de celda al estilo Excel (p.ej., "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Obtiene una celda de la hoja de cálculo especificada usando el nombre de celda al estilo Excel (p.ej., "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Obtiene una colección de celdas del libro de trabajo que coinciden con la fórmula especificada. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Obtiene un diccionario que contiene los índices y nombres de todos los gráficos en la hoja de cálculo especificada de un libro de trabajo de Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/es/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Obtiene los nombres de todas las hojas de cálculo contenidas en el libro de trabajo de Excel. |


### Ver también
* módulo [`aspose.slides.excel`](/slides/python-net/es/aspose.slides.excel)
* biblioteca [`Aspose.Slides`](/slides/python-net)