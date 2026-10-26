---
title: BinarySearchImpl()
second_title: Referência da API Aspose.Slides for C++
description: Implementação comum de busca binária.
type: docs
weight: 118
url: /pt/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) função

Implementação comum de busca binária.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos elementos na faixa |
| TValue | Tipo do valor a ser procurado |
| TCompareFunc | Tipo de função para comparação |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A faixa a ser pesquisada |
| value | const TValue\& | O valor a ser procurado |
| compareFunc | TCompareFunc | Função que compara o valor com o elemento da faixa e retorna **int32_t** (-1, 0, 1) |

### Valor de retorno

[Index](../../system/index/) do elemento encontrado ou complemento bit a bit do ponto de inserção

## Ver também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Espaço de nomes [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)