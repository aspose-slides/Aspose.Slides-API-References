---
title: RowCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la colección de filas de una tabla.
type: docs
weight: 9450
url: /es/aspose.slides/rowcollection/
---

## Clase RowCollection

Representa la colección de filas de una tabla.

```csharp
public sealed class RowCollection : DomObject<Table>, IRowCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/rowcollection/count) { get; } | Obtiene el número de filas que realmente están contenidas en la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/rowcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para múltiples hilos). Solo lectura Boolean. |
| [Item](../../aspose.slides/rowcollection/item) { get; } | Devuelve la fila en el índice especificado. Solo lectura [`Row`](../row). |
| [SyncRoot](../../aspose.slides/rowcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/rowcollection/addclone)(IRow, bool) | Crea una copia de la fila plantilla especificada e inserta en la parte inferior de una tabla. |
| [CopyTo](../../aspose.slides/rowcollection/copyto)(Array, int) | Copia todos los elementos de la colección a la matriz especificada. |
| [GetEnumerator](../../aspose.slides/rowcollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [InsertClone](../../aspose.slides/rowcollection/insertclone)(int, IRow, bool) | Crea una copia de la fila plantilla especificada e inserta en la posición especificada en una tabla. |
| [RemoveAt](../../aspose.slides/rowcollection/removeat)(int, bool) | Elimina una fila en la posición especificada de una tabla. |

### Véase también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Table](../table)
* interfaz [IRowCollection](../irowcollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->