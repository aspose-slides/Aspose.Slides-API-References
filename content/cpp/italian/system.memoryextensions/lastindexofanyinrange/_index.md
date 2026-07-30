---
title: LastIndexOfAnyInRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'ultima occorrenza di qualsiasi elemento all'interno dell'intervallo specificato in uno span.
type: docs
weight: 261
url: /it/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione


Trova l'ultima occorrenza di qualsiasi elemento all'interno dell'intervallo specificato in uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da cercare |
| lowInclusive | const T\& | Il limite inferiore dell'intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell'intervallo (inclusivo) |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento all'interno dell'intervallo, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) funzione


Trova l'ultima occorrenza di qualsiasi elemento all'interno dell'intervallo specificato in uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span da cercare |
| lowInclusive | const T\& | Il limite inferiore dell'intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell'intervallo (inclusivo) |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento all'interno dell'intervallo, o -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)