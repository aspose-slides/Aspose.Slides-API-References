---
title: AddComment()
second_title: Referencia de API de Aspose.Slides para C++
description: Agregar un nuevo comentario al final de una colección.
type: docs
weight: 14
url: /es/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) método

Agregar un nuevo comentario al final de una colección.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto plano de un nuevo comentario. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) en una presentación donde agregar un nuevo comentario. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posición en una diapositiva donde agregar un nuevo comentario. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora de creación de un comentario. |

### Valor devuelto

Comentario agregado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComment](../../icomment/)
* Clase [String](../../../system/string/)
* Clase [ISlide](../../islide/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [DateTime](../../../system/datetime/)
* Clase [ICommentCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)