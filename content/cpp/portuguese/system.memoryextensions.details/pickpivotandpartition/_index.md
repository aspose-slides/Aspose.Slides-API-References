---
title: PickPivotAndPartition()
second_title: Referência da API Aspose.Slides para C++
description: Seleciona o pivô e particiona pares chave-valor para quicksort.
type: docs
weight: 105
url: /pt/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) função

Seleciona o pivô e particiona pares chave-valor para quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo de chaves |
| TValue | O tipo de valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O span de chaves a ser particionado |
| values | [Span](../../system/span/)\<TValue\>\& | O span de valores a ser particionado |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) função para chaves |

### Valor de retorno

O índice do pivô após a partição

## Veja Também

* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)