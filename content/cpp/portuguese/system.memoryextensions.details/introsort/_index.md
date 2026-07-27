---
title: IntroSort()
second_title: Aspose.Slides para C++ Referência da API
description: Implementação interna do algoritmo introsort para pares chave-valor.
type: docs
weight: 40
url: /pt/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function

Implementação interna do algoritmo introsort para pares chave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O span de chaves a ordenar |
| values | [Span](../../system/span/)\<TValue\>\& | O span de valores a ordenar |
| depthLimit | **int32_t** | Profundidade máxima de recursão antes de mudar para heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) função para chaves |

## Veja Também

* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)