---
title: CommentCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una colección de comentarios de un autor.
type: docs
weight: 2500
url: /es/net/aspose.slides/commentcollection/
---
## CommentCollection class

Representa una colección de comentarios de un autor.

```csharp
public sealed class CommentCollection : DomObject<CommentAuthor>, ICommentCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/commentcollection/count) { get; } | Obtiene el número de elementos realmente contenidos en la colección. Solo lecturaInt32 . |
| [IsSynchronized](../../aspose.slides/commentcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lecturaBoolean . |
| [Item](../../aspose.slides/commentcollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura[`Comment`](../comment) . |
| [SyncRoot](../../aspose.slides/commentcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lecturaObject . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddComment](../../aspose.slides/commentcollection/addcomment)(string, ISlide, PointF, DateTime) | Agregar nuevo comentario al final de una colección. |
| [AddModernComment](../../aspose.slides/commentcollection/addmoderncomment)(string, ISlide, IShape, PointF, DateTime) | Añadir un nuevo comentario moderno al final de una colección. |
| [Clear](../../aspose.slides/commentcollection/clear)() | Elimina todos los comentarios de una colección. |
| [CopyTo](../../aspose.slides/commentcollection/copyto)(Array, int) | Copia todos los elementos de la colección a la matriz especificada. |
| [FindCommentByIdx](../../aspose.slides/commentcollection/findcommentbyidx)(int) | Encuentra un comentario en la colección por index. |
| [GetEnumerator](../../aspose.slides/commentcollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [InsertComment](../../aspose.slides/commentcollection/insertcomment)(int, string, ISlide, PointF, DateTime) | Inserta un nuevo comentario en una colección en el índice especificado. |
| [InsertModernComment](../../aspose.slides/commentcollection/insertmoderncomment)(int, string, ISlide, IShape, PointF, DateTime) | Inserta un nuevo comentario moderno en una colección en el índice especificado. |
| [Remove](../../aspose.slides/commentcollection/remove)(IComment) | Elimina la primera aparición del comentario especificado en una colección. |
| [RemoveAt](../../aspose.slides/commentcollection/removeat)(int) | Elimina el elemento en el índice especificado en una colección. |
| [ToArray](../../aspose.slides/commentcollection/toarray#toarray)() | Crea y devuelve una matriz con todos los comentarios. |
| [ToArray](../../aspose.slides/commentcollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz con todos los comentarios del rango especificado. |

### Ver también

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [CommentAuthor](../commentauthor)
* interface [ICommentCollection](../icommentcollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->