---
title: IntroSort()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementazione interna dell'algoritmo introsort per coppie chiave-valore.
type: docs
weight: 40
url: /it/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Implementazione interna dell'algoritmo introsort per coppie chiave-valore.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo di chiavi |
| TValue | Il tipo di valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Lo span di chiavi da ordinare |
| values | [Span](../../system/span/)\<TValue\>\& | Lo span di valori da ordinare |
| depthLimit | **int32_t** | Profondità massima di ricorsione prima di passare a heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | Funzione [Comparison](../../system/comparison/) per le chiavi |

## Vedi anche

* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)