---
title: AddModernComment
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agregar un nuevo comentario moderno al final de una colección.
type: docs
weight: 30
url: /es/aspose.slides/icommentcollection/addmoderncomment/
---

## ICommentCollection.AddModernComment método

Agregar un nuevo comentario moderno al final de una colección.

```csharp
public IModernComment AddModernComment(string text, ISlide slide, IShape shape, PointF position, 
    DateTime creationTime)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | String | Texto plano de un nuevo comentario moderno. |
| slide | ISlide | Diapositiva en una presentación donde agregar un nuevo comentario moderno. |
| shape | IShape | Forma en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | PointF | Posición en una diapositiva donde agregar un nuevo comentario moderno. |
| creationTime | DateTime | Hora de creación de un comentario moderno. |

### Valor de retorno

Comentario moderno agregado.

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ICommentAuthor newAuthor = pres.CommentAuthors.AddAuthor("Some Author", "SA");
    newAuthor.Comments.AddModernComment("This is modern comment", pres.Slides[0], null, new PointF(100, 100), DateTime.Now);

    pres.Save(outPptxFileName, SaveFormat.Pptx);
}
```

### Ver también

* interfaz [IModernComment](../../imoderncomment)
* interfaz [ISlide](../../islide)
* interfaz [IShape](../../ishape)
* interfaz [ICommentCollection](../../icommentcollection)
* espacio de nombres [Aspose.Slides](../../icommentcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->