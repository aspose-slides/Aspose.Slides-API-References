---  
title: Row
second_title: Aspose.Sildes for .NET API Reference  
description: Representa una fila en una tabla.
type: docs
weight: 9440  
url: /es/aspose.slides/row/
---

## Row class

Representa una fila en una tabla.

```csharp
public sealed class Row : CellCollection, IRow
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/cellcollection/count) { get; } | Devuelve el número de celdas en una colección. Solo lectura Int32. |
| [Height](../../aspose.slides/row/height) { get; } | Devuelve la altura de una fila. Solo lectura Double. |
| [IsSynchronized](../../aspose.slides/cellcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). Solo lectura Boolean. |
| [Item](../../aspose.slides/cellcollection/item) { get; } | Devuelve una celda por su posición. Solo lectura [`Cell`](../cell). |
| [MinimalHeight](../../aspose.slides/row/minimalheight) { get; set; } | Devuelve o establece la altura mínima posible de una fila. Lectura/escritura Double. |
| [Presentation](../../aspose.slides/cellcollection/presentation) { get; } | Devuelve la presentación principal de una CellCollection. Solo lectura [`IPresentation`](../ipresentation). |
| [RowFormat](../../aspose.slides/row/rowformat) { get; } | Devuelve el objeto RowFormat que contiene propiedades de formato para esta fila. Solo lectura [`IRowFormat`](../irowformat). |
| [Slide](../../aspose.slides/cellcollection/slide) { get; } | Devuelve la diapositiva principal de una CellCollection. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [SyncRoot](../../aspose.slides/cellcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Methods

| Name | Description |
| --- | --- |
| [CopyTo](../../aspose.slides/cellcollection/copyto)(Array, int) | Copia todos los elementos de la colección al array especificado. |
| [GetEnumerator](../../aspose.slides/cellcollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [SetTextFormat](../../aspose.slides/row/settextformat#settextformat)(IParagraphFormat) | Establece las propiedades de formato de párrafo definidas a todos los párrafos de las celdas de la fila. |
| [SetTextFormat](../../aspose.slides/row/settextformat#settextformat_1)(IPortionFormat) | Establece las propiedades de formato de porción definidas a todas las porciones de las celdas de la fila. |
| [SetTextFormat](../../aspose.slides/row/settextformat#settextformat_2)(ITextFrameFormat) | Establece las propiedades de formato de marco de texto definidas a todos los marcos de texto de las celdas de la fila. |

### See Also

* class [CellCollection](../cellcollection)  
* interface [IRow](../irow)  
* namespace [Aspose.Slides](../../aspose.slides)  
* assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  