---
title: ICommentCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una colección de comentarios de un autor.
type: docs
weight: 5090
url: /es/net/aspose.slides/icommentcollection/
---
## ICommentCollection interface

Representa una colección de comentarios de un autor.

```csharp
public interface ICommentCollection : IGenericCollection<IComment>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides/icommentcollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura[`IComment`](../icomment) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddComment](../../aspose.slides/icommentcollection/addcomment)(string, ISlide, PointF, DateTime) | Agregar nuevo comentario al final de una colección. |
| [AddModernComment](../../aspose.slides/icommentcollection/addmoderncomment)(string, ISlide, IShape, PointF, DateTime) | Añadir un nuevo comentario moderno al final de una colección. |
| [Clear](../../aspose.slides/icommentcollection/clear)() | Elimina todos los comentarios de una colección. |
| [InsertComment](../../aspose.slides/icommentcollection/insertcomment)(int, string, ISlide, PointF, DateTime) | Inserta un nuevo comentario en una colección en el índice especificado. |
| [InsertModernComment](../../aspose.slides/icommentcollection/insertmoderncomment)(int, string, ISlide, IShape, PointF, DateTime) | Inserta un nuevo comentario moderno en una colección en el índice especificado. |
| [Remove](../../aspose.slides/icommentcollection/remove)(IComment) | Elimina la primera aparición del comentario especificado en una colección. |
| [RemoveAt](../../aspose.slides/icommentcollection/removeat)(int) | Elimina el elemento en el índice especificado en una colección. |
| [ToArray](../../aspose.slides/icommentcollection/toarray#toarray)() | Crea y devuelve una matriz con todos los comentarios. |
| [ToArray](../../aspose.slides/icommentcollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz con todos los comentarios del rango especificado. |

### Ver también

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IComment](../icomment)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->