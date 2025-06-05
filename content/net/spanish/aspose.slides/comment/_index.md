---
title: Comment
second_title: Aspose.Sildes para la referencia de API de .NET
description: Representa un comentario en una diapositiva.
type: docs
weight: 2530
url: /es/aspose.slides/comment/
---

## Clase Comment

Representa un comentario en una diapositiva.

```csharp
public class Comment : IComment
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Devuelve el autor de un comentario. Solo lectura [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Devuelve o establece el tiempo de creación de un comentario. Establecer esta propiedad en MinValue significa que no se establece tiempo de comentario. Lectura/escritura DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Obtiene o establece el comentario principal. Lectura/escritura [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Devuelve o establece la posición de un comentario en una diapositiva. Lectura/escritura PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Devuelve o establece la diapositiva principal de un comentario. Solo lectura [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Devuelve o establece el texto sin formato de un comentario en una diapositiva. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Elimina el comentario y todas sus respuestas de la colección principal. |

### Ejemplos

Este ejemplo te muestra cómo agregar un comentario a una diapositiva en una presentación de PowerPoint.

```csharp
[C#]
// Instancia la clase Presentation
using (Presentation presentation = new Presentation())
{
    // Agrega una diapositiva vacía
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Agrega un autor
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Establece la posición para los comentarios
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Agrega un comentario en la diapositiva para un autor en la diapositiva 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Agrega un comentario en la diapositiva para un autor en la diapositiva 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Guarda el archivo de presentación de PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Este ejemplo te muestra cómo acceder a un comentario existente en una diapositiva en una presentación de PowerPoint.

```csharp
[C#]
// Instancia la clase Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Itera sobre CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Itera sobre Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " tiene comentario: " + comment.Text + " con Autor: " + comment.Author.Name + " publicado en el tiempo :" + comment.CreatedTime + "\n");
        }
    }
}
```

Este ejemplo te muestra cómo agregar comentarios y obtener respuestas a ellos.

```csharp
[C#]
// Instancia la clase Presentation
using (Presentation pres = new Presentation())
{
    // Agrega un comentario
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Agrega una respuesta a comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Agrega otra respuesta a comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Agrega una respuesta a una respuesta existente
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Muestra la jerarquía de comentarios en la consola
    ISlide slide = pres.Slides[0];
    var comments = slide.GetSlideComments(null);
    for (int i = 0; i < comments.Length; i++)
    {
        IComment comment = comments[i];
        while (comment.ParentComment != null)
        {
            Console.Write("\t");
            comment = comment.ParentComment;
        }
        Console.Write("{0} : {1}", comments[i].Author.Name, comments[i].Text);
        Console.WriteLine();
    }
    pres.Save("parent_comment.pptx",SaveFormat.Pptx);
    // Elimina comment1 y todas las respuestas a él
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interface [IComment](../icomment)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->