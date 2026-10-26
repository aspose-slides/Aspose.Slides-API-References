---
title: PickPivotAndPartition()
second_title: Riferimento API Aspose.Slides per C++
description: Seleziona il pivot e partiziona le coppie chiave-valore per il quicksort.
type: docs
weight: 105
url: /it/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funzione

Seleziona il pivot e partiziona le coppie chiave-valore per il quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo di chiavi |
| TValue | Il tipo di valori |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | L'intervallo di chiavi da partizionare |
| values | [Span](../../system/span/)\<TValue\>\& | L'intervallo di valori da partizionare |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funzione per le chiavi |

### Valore di ritorno

L'indice del pivot dopo la partizione

## Vedi anche

* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)