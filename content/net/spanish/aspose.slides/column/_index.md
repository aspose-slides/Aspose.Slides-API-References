---
title: Column
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una columna en una tabla.
type: docs
weight: 2440
url: /es/aspose.slides/column/
---
## Column class

Representa una columna en una tabla.

```csharp
public sealed class Column : CellCollection, IColumn
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColumnFormat](../../aspose.slides/column/columnformat) { get; } | Devuelve el objeto ColumnFormat que contiene propiedades de formato para esta columna. Solo lectura[`IColumnFormat`](../icolumnformat) . |
| [Count](../../aspose.slides/cellcollection/count) { get; } | Devuelve el número de celdas de una colección. Solo lecturaInt32 . |
| [IsSynchronized](../../aspose.slides/cellcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lecturaBoolean . |
| [Item](../../aspose.slides/cellcollection/item) { get; } | Devuelve una celda por su posición. Solo lectura[`Cell`](../cell) . |
| [Presentation](../../aspose.slides/cellcollection/presentation) { get; } | Devuelve la presentación principal de CellCollection. Solo lectura[`IPresentation`](../ipresentation) . |
| [Slide](../../aspose.slides/cellcollection/slide) { get; } | Devuelve la diapositiva principal de CellCollection. Solo lectura[`IBaseSlide`](../ibaseslide) . |
| [SyncRoot](../../aspose.slides/cellcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lecturaObject . |
| [Width](../../aspose.slides/column/width) { get; set; } | Devuelve o establece el ancho de una columna. Lectura/escrituraDouble . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CopyTo](../../aspose.slides/cellcollection/copyto)(Array, int) | Copia todos los elementos de la colección a la matriz especificada. |
| [GetEnumerator](../../aspose.slides/cellcollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [SetTextFormat](../../aspose.slides/column/settextformat#settextformat)(IParagraphFormat) | Establece propiedades de formato de párrafo definidas para todos los párrafos de celdas de columna. |
| [SetTextFormat](../../aspose.slides/column/settextformat#settextformat_1)(IPortionFormat) | Establece propiedades de formato de porción definida para todas las porciones de celdas de columna. |
| [SetTextFormat](../../aspose.slides/column/settextformat#settextformat_2)(ITextFrameFormat) | Establece propiedades de formato de marco de texto definidas para todos los marcos de texto de celdas de columna. |

### Ver también

* class [CellCollection](../cellcollection)
* interface [IColumn](../icolumn)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
