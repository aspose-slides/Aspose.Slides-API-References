---
title: ModernComment
second_title: Aspose.Sildes para referencia de API de .NET
description: Representa un comentario en una diapositiva.
type: docs
weight: 8820
url: /es/aspose.slides/moderncomment/
---

## Clase ModernComment

Representa un comentario en una diapositiva.

```csharp
public sealed class ModernComment : Comment, IModernComment
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Devuelve el autor de un comentario. Solo lectura [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Devuelve o establece la hora de creación de un comentario. Establecer esta propiedad en MinValue significa que no se establece el tiempo del comentario. Lectura/escritura DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Obtiene o establece el comentario principal. Lectura/escritura [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Devuelve o establece la posición de un comentario en una diapositiva. Lectura/escritura PointF. |
| [Shape](../../aspose.slides/moderncomment/shape) { get; } | Devuelve una forma asociada al comentario. Solo lectura [`IShape`](../ishape). |
| [Slide](../../aspose.slides/comment/slide) { get; } | Devuelve o establece la diapositiva principal de un comentario. Solo lectura [`ISlide`](../islide). |
| [Status](../../aspose.slides/moderncomment/status) { get; set; } | Obtiene o establece el estado del comentario. Lectura/escritura [`ModernCommentStatus`](../moderncommentstatus). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Devuelve o establece el texto sin formato de un comentario de diapositiva. Lectura/escritura String. |
| [TextSelectionLength](../../aspose.slides/moderncomment/textselectionlength) { get; set; } | Obtiene o establece la longitud de selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura Int32. |
| [TextSelectionStart](../../aspose.slides/moderncomment/textselectionstart) { get; set; } | Obtiene o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape. Lectura/escritura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Elimina el comentario y todas sus respuestas de la colección principal. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ICommentAuthor newAuthor = pres.CommentAuthors.AddAuthor("Some Author", "SA");
    IModernComment modernComment = newAuthor.Comments.AddModernComment("This is modern comment", pres.Slides[0], null, new PointF(100, 100), DateTime.Now);

    pres.Save(outPptxFileName, SaveFormat.Pptx);
}
```

### Ver También

* clase [Comment](../comment)
* interfaz [IModernComment](../imoderncomment)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->