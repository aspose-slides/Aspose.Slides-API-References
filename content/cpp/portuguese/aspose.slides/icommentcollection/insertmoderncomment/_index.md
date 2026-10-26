---
title: InsertModernComment()
second_title: Referência da API Aspose.Slides para C++
description: Insere um novo comentário moderno em uma coleção no índice especificado.
type: docs
weight: 53
url: /pt/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) método

Insere um novo comentário moderno em uma coleção no índice especificado.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do elemento em uma coleção no qual o comentário moderno deve ser inserido. |
| text | [System::String](../../../system/string/) | Texto simples de um novo comentário moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) em uma apresentação onde será adicionado um novo comentário moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) em um slide ao qual um novo comentário moderno está associado. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posição em um slide onde será adicionado um novo comentário moderno. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora da criação de um comentário moderno. |

### Valor de Retorno

Comentário moderno inserido.

## Veja Também

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