---
title: HeapSort()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue l'ordinamento heap su coppie chiave-valore.
type: docs
weight: 79
url: /it/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funzione

Esegue l'ordinamento heap su coppie chiave-valore.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo di chiavi |
| TValue | Il tipo di valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | L'intervallo di chiavi da ordinare |
| values | [Span](../../system/span/)\<TValue\>\& | L'intervallo di valori da ordinare |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funzione per le chiavi |

## Vedi anche

* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)