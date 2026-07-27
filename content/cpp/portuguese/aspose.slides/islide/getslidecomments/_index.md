---
title: GetSlideComments()
second_title: Referência da API Aspose.Slides para C++
description: Retorna todos os comentários de slides adicionados por um autor específico.
type: docs
weight: 118
url: /pt/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) método

Retorna todos os comentários de slides adicionados por um autor específico.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor dos comentários a serem encontrados ou null para retornar todos os comentários. |

### Valor de Retorno

Array de [IComment](../../icomment/).

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentAuthor](../../icommentauthor/)
* Classe [ISlide](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)