---
title: ContainsAnyExceptInRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se uno span di sola lettura contiene qualche elemento al di fuori dell'intervallo specificato.
type: docs
weight: 79
url: /it/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Controlla se uno span di sola lettura contiene qualche elemento al di fuori dell'intervallo specificato.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo degli elementi nello span (deve essere confrontabile) |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| lowInclusive | const T\& | Il limite inferiore (inclusivo) |
| highInclusive | const T\& | Il limite superiore (inclusivo) |

### Valore restituito

true se viene trovato qualche elemento al di fuori dell'intervallo, false altrimenti

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Controlla se uno span mutabile contiene qualche elemento al di fuori dell'intervallo specificato.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo degli elementi nello span (deve essere confrontabile) |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span mutabile in cui cercare |
| lowInclusive | const T\& | Il limite inferiore (inclusivo) |
| highInclusive | const T\& | Il limite superiore (inclusivo) |

### Valore restituito

true se viene trovato qualche elemento al di fuori dell'intervallo, false altrimenti

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)