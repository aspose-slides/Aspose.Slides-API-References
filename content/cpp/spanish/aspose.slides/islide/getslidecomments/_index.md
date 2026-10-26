---
title: GetSlideComments()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve todos los comentarios de diapositiva añadidos por un autor específico.
type: docs
weight: 118
url: /es/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) method

Devuelve todos los comentarios de diapositiva añadidos por un autor específico.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor de los comentarios a buscar o null para devolver todos los comentarios. |

### Valor de retorno

Array de [IComment](../../icomment/).

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComment](../../icomment/)
* Clase [ICommentAuthor](../../icommentauthor/)
* Clase [ISlide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)