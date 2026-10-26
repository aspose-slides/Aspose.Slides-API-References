---
title: InsertionSort()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue l'ordinamento per inserimento su coppie chiave-valore.
type: docs
weight: 66
url: /it/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funzione

Esegue l'ordinamento per inserimento su coppie chiave-valore.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo delle chiavi |
| TValue | Il tipo dei valori |

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