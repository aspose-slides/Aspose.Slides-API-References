---
title: LastIndexOfAnyExceptInRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'ultima occorrenza di qualsiasi elemento al di fuori dell'intervallo specificato all'interno di uno span.
type: docs
weight: 248
url: /it/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento al di fuori dell'intervallo specificato all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da cercare |
| lowInclusive | const T\& | Il limite inferiore dell'intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell'intervallo (inclusivo) |

### Valore di ritorno

L'indice a base zero dell'ultimo elemento al di fuori dell'intervallo, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento al di fuori dell'intervallo specificato all'interno di uno span mutabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span da cercare |
| lowInclusive | const T\& | Il limite inferiore dell'intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell'intervallo (inclusivo) |

### Valore di ritorno

L'indice a base zero dell'ultimo elemento al di fuori dell'intervallo, oppure -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)