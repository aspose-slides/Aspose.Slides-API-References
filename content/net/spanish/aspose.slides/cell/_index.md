---
title: Cell
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una celda de una tabla.
type: docs
weight: 1050
url: /es/aspose.slides/cell/
---

## Clase Celda

Representa una celda de una tabla.

```csharp
public class Cell : ICell
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Determina si el cuadro de texto está centrado dentro de una celda. Booleano de lectura/escritura. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Devuelve el objeto CellFormat que contiene propiedades de formato para esta celda. Solo de lectura [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Devuelve el número de columnas de la cuadrícula en la cuadrícula de la tabla del padre que serán abarcadas por la celda actual. Esta propiedad permite que las celdas tengan la apariencia de estar fusionadas, ya que abarcan límites verticales de otras celdas en la tabla. Solo de lectura Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Obtiene la primera columna de la celda. Solo de lectura [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Devuelve un índice de la primera columna cubierta por la celda. Solo de lectura Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Obtiene la primera fila de la celda. Solo de lectura [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Devuelve un índice de la primera fila cubierta por la celda. Solo de lectura Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Devuelve la altura de la celda. Solo de lectura Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Devuelve verdadero si la celda está fusionada con cualquier celda ajustada, falso en caso contrario. Solo de lectura Booleano. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Devuelve o establece el margen inferior en un TextFrame. Doble de lectura/escritura. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un TextFrame. Doble de lectura/escritura. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Devuelve o establece el margen derecho en un TextFrame. Doble de lectura/escritura. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Devuelve o establece el margen superior en un TextFrame. Doble de lectura/escritura. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Devuelve la altura mínima de una celda. Esta es una suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo de lectura Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo de lectura Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Devuelve una distancia desde el lado superior de una tabla hasta el lado superior de una celda. Solo de lectura Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Devuelve la presentación padre de una celda. Solo de lectura [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Devuelve el número de filas que abarca una celda fusionada. Esto se utiliza en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una fusión horizontal. Solo de lectura Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Devuelve la diapositiva padre de una celda. Solo de lectura [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Devuelve el objeto Tabla padre para una celda. Solo de lectura [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Devuelve o establece el tipo de anclaje de texto. Doble de lectura/escritura [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Devuelve el marco de texto de una celda. Solo de lectura [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Devuelve o establece el tipo de texto vertical. Doble de lectura/escritura [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Devuelve el ancho de la celda. Solo de lectura Double. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Divide la celda en dos celdas por índice de columna. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Divide la celda por altura. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Divide la celda en dos celdas por índice de fila. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Divide la celda por ancho. |

### Véase También

* interfaz [ICell](../icell)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->