---
title: Cell
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una celda de una tabla.
type: docs
weight: 1130
url: /es/aspose.slides/cell/
---
## Cell clase

Representa una celda de una tabla.

```csharp
public class Cell : ICell
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Determina si el cuadro de texto está centrado dentro de una celda. Lectura/escritura Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Devuelve el objeto CellFormat que contiene las propiedades de formato para esta celda. Solo lectura [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Devuelve el número de columnas de la cuadrícula en la tabla principal cuya cuadrícula será abarcada por la celda actual. Esta propiedad permite que las celdas tengan la apariencia de estar combinadas, ya que abarcan los límites verticales de otras celdas en la tabla. Solo lectura Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Obtiene la primera columna de la celda. Solo lectura [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Devuelve el índice de la primera columna cubierta por la celda. Solo lectura Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Obtiene la primera fila de la celda. Solo lectura [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Devuelve el índice de la primera fila cubierta por la celda. Solo lectura Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Devuelve la altura de la celda. Solo lectura Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Devuelve true si la celda está combinada con alguna celda ajustada, false en caso contrario. Solo lectura Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Devuelve o establece el margen inferior en un TextFrame. Lectura/escritura Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un TextFrame. Lectura/escritura Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Devuelve o establece el margen derecho en un TextFrame. Lectura/escritura Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Devuelve o establece el margen superior en un TextFrame. Lectura/escritura Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Devuelve la altura mínima de una celda. Esta es la suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lectura Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Devuelve la distancia desde el lado izquierdo de la tabla hasta el lado izquierdo de la celda. Solo lectura Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Devuelve la distancia desde el lado superior de la tabla hasta el lado superior de la celda. Solo lectura Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Devuelve la presentación principal de una celda. Solo lectura [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Devuelve el número de filas que abarca una celda combinada. Esto se usa en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una combinación horizontal. Solo lectura Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Devuelve la diapositiva principal de una celda. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Devuelve el objeto Table principal de una celda. Solo lectura [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Devuelve o establece el tipo de anclaje de texto. Lectura/escritura [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Devuelve el marco de texto de una celda. Solo lectura [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Devuelve o establece el tipo de texto vertical. Lectura/escritura [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Devuelve el ancho de la celda. Solo lectura Double. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Divide la celda en dos celdas por índice de columna. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Divide la celda por altura. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Divide la celda en dos celdas por índice de fila. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Divide la celda por ancho. |

### Ver también

* interfaz [ICell](../icell)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->