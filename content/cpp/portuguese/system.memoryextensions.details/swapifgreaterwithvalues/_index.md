---
title: SwapIfGreaterWithValues()
second_title: Referência da API Aspose.Slides para C++
description: Troca pares de chave-valor se a condição de comparação for atendida.
type: docs
weight: 53
url: /pt/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) função

Troca pares de chave-valor se a condição de comparação for atendida.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O intervalo de chaves |
| values | [Span](../../system/span/)\<TValue\>\& | O intervalo de valores |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) função para chaves |
| i | **int32_t** | Primeiro índice a comparar |
| j | **int32_t** | Segundo índice a comparar |

## Veja Também

* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)