---
title: SwapIfGreaterWithValues()
second_title: Riferimento API Aspose.Slides per C++
description: Scambia le coppie chiave-valore se la condizione di confronto è soddisfatta.
type: docs
weight: 53
url: /it/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) funzione

Scambia coppie chiave-valore se la condizione di confronto è soddisfatta.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo di chiavi |
| TValue | Il tipo di valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Lo span di chiavi |
| values | [Span](../../system/span/)\<TValue\>\& | Lo span di valori |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funzione per le chiavi |
| i | **int32_t** | Primo indice da confrontare |
| j | **int32_t** | Secondo indice da confrontare |

## Vedi anche

* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)