---
title: ContainsAnyInRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se uno span di sola lettura contiene qualche elemento nell'intervallo specificato.
type: docs
weight: 92
url: /it/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione

Verifica se uno span di sola lettura contiene qualche elemento nell'intervallo specificato.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span (deve essere confrontabile) |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| lowInclusive | const T\& | Il limite inferiore (inclusivo) |
| highInclusive | const T\& | Il limite superiore (inclusivo) |

### Valore di ritorno

true se viene trovato qualche elemento nell'intervallo, false altrimenti

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) funzione

Verifica se uno span mutabile contiene qualche elemento nell'intervallo specificato.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span (deve essere confrontabile) |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span mutabile in cui cercare |
| lowInclusive | const T\& | Il limite inferiore (inclusivo) |
| highInclusive | const T\& | Il limite superiore (inclusivo) |

### Valore di ritorno

true se viene trovato qualche elemento nell'intervallo, false altrimenti

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)