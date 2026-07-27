---
title: GetSlideComments()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve todos los comentarios de diapositiva agregados por un autor específico.
type: docs
weight: 209
url: /es/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) método

Devuelve todos los comentarios de diapositiva agregados por un autor específico.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor de los comentarios a buscar o null para devolver todos los comentarios. |

### Valor devuelto

Matriz de [Comment](../../comment/).

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComment](../../icomment/)
* Clase [ICommentAuthor](../../icommentauthor/)
* Clase [Slide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)