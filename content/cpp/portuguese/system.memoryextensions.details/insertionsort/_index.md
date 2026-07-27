---
title: InsertionSort()
second_title: Referência da API Aspose.Slides for C++
description: Executa ordenação por inserção em pares de chave-valor.
type: docs
weight: 66
url: /pt/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) função

Executa ordenação por inserção em pares chave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A faixa de chaves a ser ordenada |
| values | [Span](../../system/span/)\<TValue\>\& | A faixa de valores a ser ordenada |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) função para chaves |

## Ver também

* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)