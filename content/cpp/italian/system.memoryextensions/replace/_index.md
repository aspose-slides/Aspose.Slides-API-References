---
title: Replace()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce tutte le occorrenze di un valore con un nuovo valore in uno Span.
type: docs
weight: 287
url: /it/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) funzione

Sostituisce tutte le occorrenze di un valore con un nuovo valore in un [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span da modificare in loco |
| oldValue | const T\& | Il valore da cercare e sostituire |
| newValue | const T\& | Il nuovo valore con cui sostituire oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) funzione

Copia gli elementi da sorgente a destinazione, sostituendo i valori specificati durante la copia.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La [ReadOnlySpan](../../system/readonlyspan/) sorgente da copiare |
| destination | [Span](../../system/span/)\<T\>\& | La [Span](../../system/span/) destinazione a cui copiare |
| oldValue | const T\& | Il valore da cercare e sostituire durante la copia |
| newValue | const T\& | Il nuovo valore con cui sostituire oldValue |

## Vedi anche

* Classe [Span](../../system/span/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)