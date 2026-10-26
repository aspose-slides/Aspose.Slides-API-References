---
title: Cell class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/cell/
---
## Clase Cell

Representa una celda de una tabla.

El tipo Cell expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/es/aspose.slides/cell/offset_x/) | Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda.<br/>            Solo lectura **float**. |
| [`offset_y`](/slides/python-net/es/aspose.slides/cell/offset_y/) | Devuelve una distancia desde el lado superior de una tabla hasta el lado superior de una celda.<br/>            Solo lectura **float**. |
| [`first_row_index`](/slides/python-net/es/aspose.slides/cell/first_row_index/) | Devuelve el índice de la primera fila cubierta por la celda.<br/>            Solo lectura **int**. |
| [`first_column_index`](/slides/python-net/es/aspose.slides/cell/first_column_index/) | Devuelve el índice de la primera columna cubierta por la celda.<br/>            Solo lectura **int**. |
| [`width`](/slides/python-net/es/aspose.slides/cell/width/) | Devuelve el ancho de la celda.<br/>            Solo lectura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/cell/height/) | Devuelve la altura de la celda.<br/>            Solo lectura **float**. |
| [`minimal_height`](/slides/python-net/es/aspose.slides/cell/minimal_height/) | Devuelve la altura mínima de una celda.<br/>            Esta es una suma de las alturas mínimas de todas las filas cubiertas por la celda.<br/>            Solo lectura **float**. |
| [`margin_left`](/slides/python-net/es/aspose.slides/cell/margin_left/) | Devuelve o establece el margen izquierdo en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_right`](/slides/python-net/es/aspose.slides/cell/margin_right/) | Devuelve o establece el margen derecho en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_top`](/slides/python-net/es/aspose.slides/cell/margin_top/) | Devuelve o establece el margen superior en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_bottom`](/slides/python-net/es/aspose.slides/cell/margin_bottom/) | Devuelve o establece el margen inferior en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`text_vertical_type`](/slides/python-net/es/aspose.slides/cell/text_vertical_type/) | Devuelve o establece el tipo de texto vertical.<br/>            Lectura/escritura [`TextVerticalType`](/slides/python-net/es/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/es/aspose.slides/cell/text_anchor_type/) | Devuelve o establece el tipo de anclaje de texto.<br/>            Lectura/escritura [`TextAnchorType`](/slides/python-net/es/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/es/aspose.slides/cell/anchor_center/) | Determina si el cuadro de texto está centrado dentro de una celda.<br/>            Lectura/escritura **bool**. |
| [`first_row`](/slides/python-net/es/aspose.slides/cell/first_row/) | Obtiene la primera fila de la celda.<br/>            Solo lectura [`IRow`](/slides/python-net/es/aspose.slides/irow). |
| [`first_column`](/slides/python-net/es/aspose.slides/cell/first_column/) | Obtiene la primera columna de la celda.<br/>            Solo lectura [`IColumn`](/slides/python-net/es/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/es/aspose.slides/cell/col_span/) | Devuelve el número de columnas de la cuadrícula en la tabla principal que debe ser abarcado por la celda actual. Esta propiedad permite que las celdas tengan la apariencia de estar combinadas, ya que abarcan los límites verticales de otras celdas en la tabla.<br/>            Solo lectura **int**. |
| [`row_span`](/slides/python-net/es/aspose.slides/cell/row_span/) | Devuelve el número de filas que abarca una celda combinada. Esto se utiliza en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una combinación horizontal.<br/>            Solo lectura **int**. |
| [`text_frame`](/slides/python-net/es/aspose.slides/cell/text_frame/) | Devuelve el marco de texto de una celda.<br/>            Solo lectura [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe). |
| [`table`](/slides/python-net/es/aspose.slides/cell/table/) | Devuelve el objeto Table padre de una celda.<br/>            Solo lectura [`ITable`](/slides/python-net/es/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/es/aspose.slides/cell/is_merged_cell/) | Devuelve verdadero si la celda está combinada con alguna celda ajustada, falso en caso contrario.<br/>            Solo lectura **bool**. |
| [`cell_format`](/slides/python-net/es/aspose.slides/cell/cell_format/) | Devuelve el objeto CellFormat que contiene las propiedades de formato para esta celda.<br/>            Solo lectura [`ICellFormat`](/slides/python-net/es/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/es/aspose.slides/cell/slide/) | Devuelve la diapositiva padre de una celda.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/cell/presentation/) | Devuelve la presentación padre de una celda.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |

## Métodos

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/es/aspose.slides/cell/split_by_col_span/#int) | Divide la celda en dos celdas según el índice de columna. |
| [`split_by_row_span(self, index)`](/slides/python-net/es/aspose.slides/cell/split_by_row_span/#int) | Divide la celda en dos celdas según el índice de fila. |
| [`split_by_height(self, height)`](/slides/python-net/es/aspose.slides/cell/split_by_height/#float) | Divide la celda por altura. |
| [`split_by_width(self, width)`](/slides/python-net/es/aspose.slides/cell/split_by_width/#float) | Divide la celda por ancho. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)