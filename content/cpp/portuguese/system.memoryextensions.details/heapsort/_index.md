---
title: HeapSort()
second_title: Referência da API Aspose.Slides para C++
description: Executa ordenação heap em pares de chave-valor.
type: docs
weight: 79
url: /pt/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) função


Executa ordenação heap em pares de chave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O intervalo de chaves a ser ordenado |
| values | [Span](../../system/span/)\<TValue\>\& | O intervalo de valores a ser ordenado |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) função para chaves |

## Veja Também

* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)