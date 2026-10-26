---
title: ContainsAny()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se uno span di sola lettura contiene uno dei due valori.
type: docs
weight: 53
url: /it/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione

Verifica se un span di sola lettura contiene uno dei due valori.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |

### Valore di ritorno

true se uno dei valori è trovato nello span, false altrimenti

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funzione

Verifica se un span di sola lettura contiene uno dei tre valori.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |
| value2 | const T\& | Il terzo valore da cercare |

### Valore di ritorno

true se uno dei valori è trovato nello span, false altrimenti

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) funzione

Verifica se un span modificabile contiene uno dei due valori.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |

### Valore di ritorno

true se uno dei valori è trovato nello span, false altrimenti

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funzione

Verifica se un span modificabile contiene uno dei tre valori.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |
| value2 | const T\& | Il terzo valore da cercare |

### Valore di ritorno

true se uno dei valori è trovato nello span, false altrimenti

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Verifica se un span di sola lettura contiene qualche valore da un altro span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di valori da cercare |

### Valore di ritorno

true se qualche valore di values è trovato nello span, false altrimenti

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Verifica se un span modificabile contiene qualche valore da un span di sola lettura.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di sola lettura di valori da cercare |

### Valore di ritorno

true se qualche valore di values è trovato nello span, false altrimenti

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)