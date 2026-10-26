---
title: InsertModernComment()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta un nuevo comentario moderno en una colección en el índice especificado.
type: docs
weight: 53
url: /es/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) método


Inserte un nuevo comentario moderno en una colección en el índice especificado.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice del elemento en una colección en el que se debe insertar el comentario moderno. |
| text | [System::String](../../../system/string/) | Texto sin formato de un nuevo comentario moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) en una presentación donde se agrega un nuevo comentario moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posición en una diapositiva donde se agrega un nuevo comentario moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora de creación de un comentario moderno. |

### Valor devuelto

Comentario moderno insertado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IModernComment](../../imoderncomment/)
* Clase [String](../../../system/string/)
* Clase [ISlide](../../islide/)
* Clase [IShape](../../ishape/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [DateTime](../../../system/datetime/)
* Clase [ICommentCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)