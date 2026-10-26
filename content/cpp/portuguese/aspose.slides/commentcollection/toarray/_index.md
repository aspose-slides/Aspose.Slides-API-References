---
title: ToArray()
second_title: Aspose.Slides para C++ Referência da API
description: Cria e retorna um array com todos os comentários.
type: docs
weight: 105
url: /pt/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() método

Cria e retorna um array com todos os comentários.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### Valor de Retorno

Array de [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) método

Cria e retorna um array com todos os comentários do intervalo especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **int32_t** | Um índice do primeiro comentário a ser retornado. |
| count | **int32_t** | Um número de comentários a ser retornado. |

### Valor de Retorno

Array de [Comment](../../comment/).

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [CommentCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)