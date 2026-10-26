---
title: Heapify()
second_title: Aspose.Slides para C++ Referência da API
description: Mantém a propriedade de heap para pares chave-valor.
type: docs
weight: 92
url: /pt/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) função

Mantém a propriedade de heap para pares chave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O span de chaves no heap |
| values | [Span](../../system/span/)\<TValue\>\& | O span de valores no heap |
| n | **int32_t** | Tamanho do heap |
| i | **int32_t** | [Index](../../system/index/) para iniciar heapificação a partir de |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) função para chaves |

## Veja Também

* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)