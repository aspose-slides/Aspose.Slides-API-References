---
title: Count()
second_title: Riferimento API Aspose.Slides per C++
description: Conta le occorrenze di un valore in uno span di sola lettura.
type: docs
weight: 118
url: /it/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) function

Conta le occorrenze di un valore in uno span di sola lettura.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value | const T\& | Il valore da contare |

### Valore restituito

Il numero di volte in cui il valore appare nello span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Conta le occorrenze di uno span all'interno di un altro span di sola lettura.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di cui contare le occorrenze |

### Valore restituito

Il numero di volte in cui il valore appare nello span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) function

Conta le occorrenze di un singolo valore in uno Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| value | const T\& | Il valore di cui contare le occorrenze |

### Valore restituito

Il numero di occorrenze del valore nello span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Conta le occorrenze di un ReadOnlySpan<T> in un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span contenente i valori da contare |

### Valore restituito

Il numero di occorrenze dello span di valori nello span di destinazione

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)