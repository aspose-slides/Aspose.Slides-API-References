---
title: SequenceEqualImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se due span sono uguali a partire dalle posizioni specificate.
type: docs
weight: 27
url: /it/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) funzione

Controlla se due span sono uguali a partire dalle posizioni specificate.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Primo span |
| start | const **int32_t** | Indice iniziale nello span first |
| length | **int32_t** | Numero di elementi da confrontare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span second |

### Valore restituito

true se gli intervalli specificati sono uguali, false altrimenti

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Spazio dei nomi [System::MemoryExtensions::Details](../)
* Libreria [Aspose.Slides](../../)