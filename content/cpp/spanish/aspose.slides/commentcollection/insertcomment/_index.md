---
title: InsertComment()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserta un nuevo comentario en una colección en el índice especificado.
type: docs
weight: 79
url: /es/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) método

Inserta un nuevo comentario en una colección en el índice especificado.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice del elemento en una colección en el que se debe insertar el comentario. |
| text | [System::String](../../../system/string/) | Texto sin formato de un nuevo comentario. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) en una presentación donde se debe agregar un nuevo comentario. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posición en una diapositiva donde se debe agregar un nuevo comentario. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora de creación del comentario. |

### Valor devuelto

Comentario insertado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComment](../../icomment/)
* Clase [String](../../../system/string/)
* Clase [ISlide](../../islide/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [DateTime](../../../system/datetime/)
* Clase [CommentCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)