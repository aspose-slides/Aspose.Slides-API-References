---
title: AddComment()
second_title: Referência da API Aspose.Slides para C++
description: Adicionar novo comentário ao final de uma coleção.
type: docs
weight: 14
url: /pt/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

Adicionar novo comentário ao final de uma coleção.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto simples de um novo comentário. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) em uma apresentação onde adicionar um novo comentário. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posição em um slide onde adicionar um novo comentário. |
| creationTime | [System::DateTime](../../../system/datetime/) | Horário de criação do comentário. |

### Valor de Retorno

Comentário adicionado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)