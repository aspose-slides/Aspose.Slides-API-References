---
title: GetSlideComments()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna todos os comentários de slide adicionados por um autor específico.
type: docs
weight: 209
url: /pt/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) método

Retorna todos os comentários de slide adicionados por um autor específico.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor dos comentários a encontrar ou nulo para retornar todos os comentários. |

### Valor de Retorno

Array de [Comment](../../comment/).

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentAuthor](../../icommentauthor/)
* Classe [Slide](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)