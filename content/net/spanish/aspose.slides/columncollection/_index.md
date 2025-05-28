---
title: ColumnCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una colección de columnas en una tabla.
type: docs
weight: 2510
url: /es/aspose.slides/columncollection/
---

## Clase ColumnCollection

Representa una colección de columnas en una tabla.

```csharp
public sealed class ColumnCollection : DomObject<RowCollection>, IColumnCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/columncollection/count) { get; } | Devuelve el número de columnas en una colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/columncollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/columncollection/item) { get; } | Devuelve la columna en el índice especificado. Solo lectura [`Column`](../column). |
| [SyncRoot](../../aspose.slides/columncollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/columncollection/addclone)(IColumn, bool) | Crea una copia de la fila plantilla especificada e inserta al final de una tabla. |
| [CopyTo](../../aspose.slides/columncollection/copyto)(Array, int) | Copia todos los elementos de la colección al array especificado. |
| [GetEnumerator](../../aspose.slides/columncollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [InsertClone](../../aspose.slides/columncollection/insertclone)(int, IColumn, bool) | Crea una copia de la columna plantilla especificada e inserta en la posición especificada en una tabla. |
| [RemoveAt](../../aspose.slides/columncollection/removeat)(int, bool) | Elimina una columna en la posición especificada de una tabla. |

### Véase también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [RowCollection](../rowcollection)
* interfaz [IColumnCollection](../icolumncollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->