---
title: AddModernComment()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona novo comentário moderno ao final de uma coleção.
type: docs
weight: 27
url: /pt/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) método

Adiciona novo comentário moderno ao final de uma coleção.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto simples de um novo comentário moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) em uma apresentação onde adicionar um novo comentário moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) em um slide ao qual um novo comentário moderno está associado. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posição em um slide onde adicionar um novo comentário moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Tempo de criação de um comentário moderno. |

### Valor de Retorno

Comentário moderno adicionado.

## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IModernComment](../../imoderncomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [IShape](../../ishape/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)