---
title: Fila
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una fila en una tabla.
type: docs
weight: 9440
url: /es/aspose.slides/row/
---

## Clase Fila

Representa una fila en una tabla.

```csharp
public sealed class Row : CellCollection, IRow
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/cellcollection/count) { get; } | Devuelve el número de celdas en una colección. Solo lectura Int32. |
| [Height](../../aspose.slides/row/height) { get; } | Devuelve la altura de una fila. Solo lectura Double. |
| [IsSynchronized](../../aspose.slides/cellcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/cellcollection/item) { get; } | Devuelve una celda por su posición. Solo lectura [`Cell`](../cell). |
| [MinimalHeight](../../aspose.slides/row/minimalheight) { get; set; } | Devuelve o establece la altura mínima posible de una fila. Lectura/escritura Double. |
| [Presentation](../../aspose.slides/cellcollection/presentation) { get; } | Devuelve la presentación principal de una CellCollection. Solo lectura [`IPresentation`](../ipresentation). |
| [RowFormat](../../aspose.slides/row/rowformat) { get; } | Devuelve el objeto RowFormat que contiene las propiedades de formato para esta fila. Solo lectura [`IRowFormat`](../irowformat). |
| [Slide](../../aspose.slides/cellcollection/slide) { get; } | Devuelve la diapositiva principal de una CellCollection. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [SyncRoot](../../aspose.slides/cellcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CopyTo](../../aspose.slides/cellcollection/copyto)(Array, int) | Copia todos los elementos de la colección a la matriz especificada. |
| [GetEnumerator](../../aspose.slides/cellcollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [SetTextFormat](../../aspose.slides/row/settextformat#settextformat)(IParagraphFormat) | Establece las propiedades de formato de párrafo definidas en todos los párrafos de las celdas de la fila. |
| [SetTextFormat](../../aspose.slides/row/settextformat#settextformat_1)(IPortionFormat) | Establece las propiedades de formato de porción definidas en todas las porciones de las celdas de la fila. |
| [SetTextFormat](../../aspose.slides/row/settextformat#settextformat_2)(ITextFrameFormat) | Establece las propiedades de formato de cuadro de texto definidas en todos los cuadros de texto de las celdas de la fila. |

### Véase También

* clase [CellCollection](../cellcollection)
* interfaz [IRow](../irow)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->