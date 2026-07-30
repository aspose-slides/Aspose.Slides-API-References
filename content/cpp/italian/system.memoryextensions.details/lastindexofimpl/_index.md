---
title: LastIndexOfImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'ultimo indice di un valore in uno span.
type: docs
weight: 14
url: /it/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function


Trova l'ultimo indice di un valore in uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) da cercare |
| length | **int32_t** | Lunghezza entro cui cercare |
| value | const T\& | Valore da trovare |

### Valore restituito

Ultimo indice del valore, o -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Spazio dei nomi [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)