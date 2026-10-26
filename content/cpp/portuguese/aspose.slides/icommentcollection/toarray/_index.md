---
title: ToArray()
second_title: Referência da API Aspose.Slides para C++
description: Cria e retorna um array com todos os comentários.
type: docs
weight: 66
url: /pt/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() method


Cria e retorna um array com todos os comentários.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```


### Valor de Retorno

Array de [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) method


Cria e retorna um array com todos os comentários do intervalo especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **int32_t** | Um índice do primeiro comentário a ser retornado. |
| count | **int32_t** | Um número de comentários a ser retornado. |

### Valor de Retorno

Array de [IComment](../../icomment/).

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)