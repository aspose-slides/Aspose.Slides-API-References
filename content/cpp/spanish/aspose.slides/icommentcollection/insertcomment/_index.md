---
title: InsertComment()
second_title: Referencia de API de Aspose.Slides para C++
description: Insertar un nuevo comentario en una colección en el índice especificado.
type: docs
weight: 40
url: /es/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

Insertar un nuevo comentario en una colección en el índice especificado.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice del elemento en la colección en el que se debe insertar el comentario. |
| text | [System::String](../../../system/string/) | Texto sin formato de un nuevo comentario. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) en una presentación donde se agregará un nuevo comentario. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posición en la diapositiva donde se agregará un nuevo comentario. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora de creación del comentario. |

### Valor de retorno

Comentario insertado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)