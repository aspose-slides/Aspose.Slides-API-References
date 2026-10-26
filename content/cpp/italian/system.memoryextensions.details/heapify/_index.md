---
title: Heapify()
second_title: Riferimento API di Aspose.Slides per C++
description: Mantiene la proprietà di heap per coppie chiave-valore.
type: docs
weight: 92
url: /it/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Mantiene la proprietà di heap per coppie chiave-valore.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo delle chiavi |
| TValue | Il tipo dei valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | L’intervallo di chiavi nell'heap |
| values | [Span](../../system/span/)\<TValue\>\& | L’intervallo di valori nell'heap |
| n | **int32_t** | Dimensione dell'heap |
| i | **int32_t** | [Index](../../system/index/) da heapify a partire da |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funzione per le chiavi |

## Vedi anche

* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)