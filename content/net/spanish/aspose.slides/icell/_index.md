---
title: ICell
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una celda en una tabla.
type: docs
weight: 5250
url: /es/aspose.slides/icell/
---

## Interfaz ICell

Representa una celda en una tabla.

```csharp
public interface ICell : ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Determina si el cuadro de texto está centrado dentro de una celda. Booleano de lectura/escritura. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Devuelve el objeto CellFormat que contiene propiedades de formato para esta celda. Solo lectura [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Devuelve el número de columnas de cuadrícula en la cuadrícula de la tabla del padre que serán abarcadas por la celda actual. Esta propiedad permite que las celdas tengan la apariencia de estar fusionadas, ya que abarcan los límites verticales de otras celdas en la tabla. Solo lectura Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Obtiene la primera columna de la celda. Solo lectura [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Devuelve un índice de la primera columna, cubierta por la celda. Solo lectura Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Obtiene la primera fila de la celda. Solo lectura [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Devuelve un índice de la primera fila, cubierta por la celda. Solo lectura Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Devuelve la altura de la celda. Solo lectura Doble. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Devuelve verdadero si la celda está fusionada con alguna celda ajustada, falso de lo contrario. Solo lectura Booleano. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Devuelve o establece el margen inferior en un TextFrame. Doble de lectura/escritura. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un TextFrame. Doble de lectura/escritura. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Devuelve o establece el margen derecho en un TextFrame. Doble de lectura/escritura. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Devuelve o establece el margen superior en un TextFrame. Doble de lectura/escritura. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Devuelve la altura mínima de una celda. Esta es una suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lectura Doble. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo lectura Doble. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Devuelve una distancia desde el lado superior de una tabla hasta el lado superior de una celda. Solo lectura Doble. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Devuelve el número de filas que abarca una celda fusionada. Esto se utiliza en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una fusión horizontal. Solo lectura Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Devuelve el objeto Table padre para una celda. Solo lectura [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Devuelve o establece el tipo de anclaje del texto. Doble de lectura/escritura [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Devuelve el marco de texto de una celda. Solo lectura [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Devuelve o establece el tipo de texto vertical. Doble de lectura/escritura [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Devuelve el ancho de la celda. Solo lectura Doble. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Divide la celda en dos celdas por índice de columna. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Divide la celda por altura. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Divide la celda en dos celdas por índice de fila. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Divide la celda por ancho. |

### Ver También

* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->