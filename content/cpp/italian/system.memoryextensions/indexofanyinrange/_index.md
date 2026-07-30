---
title: IndexOfAnyInRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'indice del primo elemento che è nell'intervallo specificato in un ReadOnlySpan<T>
type: docs
weight: 196
url: /it/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione

Trova l'indice del primo elemento che è nell'intervallo specificato in un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| lowInclusive | const T\& | Il limite inferiore dell'intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell'intervallo (inclusivo) |

### Valore restituito

L'indice a base zero del primo elemento all'interno dell'intervallo, o -1 se non trovato

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) funzione

Trova l'indice del primo elemento che è nell'intervallo specificato in un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| lowInclusive | const T\& | Il limite inferiore dell'intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell'intervallo (inclusivo) |

### Valore restituito

L'indice a base zero del primo elemento all'interno dell'intervallo, o -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)