---
title: IndexOfAnyExceptInRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'indice del primo elemento che è fuori dall'intervallo specificato in un ReadOnlySpan<T>
type: docs
weight: 183
url: /it/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Trova l’indice del primo elemento che è fuori dall’intervallo specificato in un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da cercare |
| lowInclusive | const T\& | Il limite inferiore dell’intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell’intervallo (inclusivo) |

### Valore di ritorno

L’indice basato su zero del primo elemento fuori dall’intervallo, oppure -1 se non trovato

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Trova l’indice del primo elemento che è fuori dall’intervallo specificato in un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span da cercare |
| lowInclusive | const T\& | Il limite inferiore dell’intervallo (inclusivo) |
| highInclusive | const T\& | Il limite superiore dell’intervallo (inclusivo) |

### Valore di ritorno

L’indice basato su zero del primo elemento fuori dall’intervallo, oppure -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)