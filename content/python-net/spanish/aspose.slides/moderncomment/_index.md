---
title: ModernComment class
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/moderncomment/
---
## ModernComment class

Representa un comentario en una diapositiva.

**Herencia:**[`ModernComment`](/slides/python-net/es/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/es/aspose.slides/comment)

El tipo ModernComment expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/es/aspose.slides/moderncomment/text/) | Devuelve o establece el texto sin formato de un comentario de diapositiva.<br/>            Lectura/escritura **str**. |
| [`created_time`](/slides/python-net/es/aspose.slides/moderncomment/created_time/) | Devuelve o establece la hora de creación de un comentario.<br/>            Establecer esta propiedad a **System.DateTime** significa que no se establece la hora del comentario.<br/>            Lectura/escritura **System.DateTime**. |
| [`slide`](/slides/python-net/es/aspose.slides/moderncomment/slide/) | Devuelve o establece la diapositiva principal de un comentario.<br/>            Solo lectura [`ISlide`](/slides/python-net/es/aspose.slides/islide). |
| [`author`](/slides/python-net/es/aspose.slides/moderncomment/author/) | Devuelve el autor de un comentario.<br/>            Solo lectura [`ICommentAuthor`](/slides/python-net/es/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/es/aspose.slides/moderncomment/position/) | Devuelve o establece la posición de un comentario en una diapositiva.<br/>            Lectura/escritura **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/es/aspose.slides/moderncomment/parent_comment/) | Obtiene o establece el comentario padre.<br/>            Lectura/escritura [`IComment`](/slides/python-net/es/aspose.slides/icomment). |
| [`shape`](/slides/python-net/es/aspose.slides/moderncomment/shape/) | Devuelve una forma asociada al comentario.<br/>            Solo lectura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/es/aspose.slides/moderncomment/text_selection_start/) | Obtiene o establece la posición inicial de la selección de texto en el marco de texto si el comentario está asociado con AutoShape.<br/>            Lectura/escritura **int**. |
| [`text_selection_length`](/slides/python-net/es/aspose.slides/moderncomment/text_selection_length/) | Obtiene o establece la longitud de la selección de texto en el marco de texto si el comentario está asociado con AutoShape.<br/>            Lectura/escritura **int**. |
| [`status`](/slides/python-net/es/aspose.slides/moderncomment/status/) | Obtiene o establece el estado del comentario.<br/>            Lectura/escritura [`ModernCommentStatus`](/slides/python-net/es/aspose.slides/moderncommentstatus). |

## Métodos

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/es/aspose.slides/moderncomment/remove/#) | Elimina el comentario y todas sus respuestas de la colección principal. |


### Ver también
* clase [`Comment`](/slides/python-net/es/aspose.slides/comment)
* clase [`ModernComment`](/slides/python-net/es/aspose.slides/moderncomment)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)