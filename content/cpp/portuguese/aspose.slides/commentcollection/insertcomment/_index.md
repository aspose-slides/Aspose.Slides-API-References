---
title: InsertComment()
second_title: Referência da API Aspose.Slides para C++
description: Insere um novo comentário em uma coleção no índice especificado.
type: docs
weight: 79
url: /pt/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) método

Insere um novo comentário em uma coleção no índice especificado.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do elemento em uma coleção no qual o comentário deve ser inserido. |
| text | [System::String](../../../system/string/) | Texto simples de um novo comentário. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) em uma apresentação onde adicionar um novo comentário. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posição em um slide onde adicionar um novo comentário. |
| creationTime | [System::DateTime](../../../system/datetime/) | Hora da criação de um comentário. |

### Valor de Retorno

Comentário inserido.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [CommentCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)