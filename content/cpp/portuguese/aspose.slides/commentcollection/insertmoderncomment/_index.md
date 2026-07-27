---
title: InsertModernComment()
second_title: Referência da API Aspose.Slides para C++
description: Insere um novo comentário moderno em uma coleção no índice especificado.
type: docs
weight: 92
url: /pt/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) método

Insere um novo comentário moderno em uma coleção no índice especificado.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice do elemento em uma coleção onde o comentário moderno deve ser inserido. |
| text | [System::String](../../../system/string/) | Texto simples de um novo comentário moderno. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) em uma apresentação onde adicionar um novo comentário moderno. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) em um slide ao qual um novo comentário moderno está associado. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posição em um slide onde adicionar um novo comentário moderno. |
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
* Classe [CommentCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)