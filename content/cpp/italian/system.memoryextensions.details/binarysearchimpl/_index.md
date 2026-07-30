---
title: BinarySearchImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementazione comune della ricerca binaria.
type: docs
weight: 118
url: /it/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) funzione

Implementazione comune della ricerca binaria.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo degli elementi nello span |
| TValue | Tipo del valore da cercare |
| TCompareFunc | Tipo di funzione per il confronto |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da cercare |
| value | const TValue\& | Il valore da cercare |
| compareFunc | TCompareFunc | Funzione che confronta il valore con l'elemento dello span e restituisce **int32_t** (-1, 0, 1) |

### Valore di ritorno

[Index](../../system/index/) dell'elemento trovato o complemento a bit del punto di inserimento

## Vedi anche

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)