---
title: AddModernComment()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un nuevo comentario moderno al final de una colección.
type: docs
weight: 66
url: /es/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) método

Agrega un nuevo comentario moderno al final de una colección.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto plano de un nuevo comentario moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) en una presentación donde agregar un nuevo comentario moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posición en una diapositiva donde agregar un nuevo comentario moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora de creación de un comentario moderno. |

### Valor de retorno

Comentario moderno añadido.

## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IModernComment](../../imoderncomment/)
* Clase [String](../../../system/string/)
* Clase [ISlide](../../islide/)
* Clase [IShape](../../ishape/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [DateTime](../../../system/datetime/)
* Clase [CommentCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)