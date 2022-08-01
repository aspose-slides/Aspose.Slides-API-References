---
title: ICell
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una celda en una tabla.
type: docs
weight: 4950
url: /es/net/aspose.slides/icell/
---
## ICell interface

Representa una celda en una tabla.

```csharp
public interface ICell : ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Determina si el cuadro de texto está centrado o no dentro de una celda. Lectura/escrituraBoolean . |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura[`ISlideComponent`](../islidecomponent) . |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Devuelve el objeto CellFormat que contiene propiedades de formato para esta celda. Solo lectura[`ICellFormat`](../icellformat) . |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Devuelve el número de columnas de la cuadrícula en la tabla grid de la tabla principal que abarcará la celda actual. Esta propiedad permite que las celdas tengan la apariencia de estar fusionadas, ya que abarcan los límites verticales de otras celdas de la tabla. Solo lecturaInt32 . |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Obtiene la primera columna de la celda. Solo lectura[`IColumn`](../icolumn) . |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Devuelve un índice de la primera columna, cubierto por la celda. Solo lecturaInt32 . |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Obtiene la primera fila de la celda. Solo lectura[`IRow`](../irow) . |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Devuelve un índice de la primera fila, cubierto por la celda. Solo lecturaInt32 . |
| [Height](../../aspose.slides/icell/height) { get; } | Devuelve el alto de la celda. Solo lecturaDouble . |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Devuelve verdadero si la celda se fusiona con cualquier celda ajustada, falso de lo contrario. Solo lecturaBoolean . |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Devuelve o establece el margen inferior en un TextFrame. Lectura/escrituraDouble |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Devuelve o establece el margen izquierdo en un TextFrame. Lectura/escrituraDouble |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Devuelve o establece el margen derecho en un TextFrame. Lectura/escrituraDouble |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Devuelve o establece el margen superior en un TextFrame. Lectura/escrituraDouble |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Devuelve la altura mínima de una celda. Esta es la suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lecturaDouble . |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Devuelve una distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo lecturaDouble . |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Devuelve la distancia desde la parte superior de una tabla hasta la parte superior de una celda. Solo lecturaDouble . |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Devuelve el número de filas que abarca una celda combinada. Esto se usa en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una combinación horizontal. Solo lecturaInt32 . |
| [Table](../../aspose.slides/icell/table) { get; } | Devuelve el objeto Tabla principal de una celda. Solo lectura[`ITable`](../itable) . |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Devuelve o establece el tipo de ancla de texto. Lectura/escritura[`TextAnchorType`](../textanchortype) . |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Devuelve el marco de texto de una celda. Solo lectura[`ITextFrame`](../itextframe) . |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Devuelve o establece el tipo de texto vertical. Lectura/escritura[`TextVerticalType`](../textverticaltype) . |
| [Width](../../aspose.slides/icell/width) { get; } | Devuelve el ancho de la celda. Solo lecturaDouble . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Divide la celda en dos celdas por índice de columna. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Divide la celda por altura. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Divide la celda en dos celdas por índice de fila. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Divide la celda por ancho. |

### Ver también

* interface [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
