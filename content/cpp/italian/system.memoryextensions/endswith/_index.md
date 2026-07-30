---
title: EndsWith()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se un ReadOnlySpan<T> termina con un valore singolo.
type: docs
weight: 131
url: /it/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

Determina se un ReadOnlySpan<T> termina con un valore singolo.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare |
| value | const T\& | Il valore da verificare alla fine dello span |

### Valore di ritorno

true se lo span termina con il valore, false altrimenti

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Determina se un ReadOnlySpan<T> termina con un altro ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare alla fine dello span di destinazione |

### Valore di ritorno

true se lo span termina con lo span valore, false altrimenti

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Determina se un Span<T> termina con un ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span da verificare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare alla fine dello span di destinazione |

### Valore di ritorno

true se lo span termina con lo span valore, false altrimenti

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

Determina se un ReadOnlySpan<T> termina con un Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare |
| value | const [Span](../../system/span/)\<T\>\& | Lo span da verificare alla fine dello span di destinazione |

### Valore di ritorno

true se lo span termina con lo span valore, false altrimenti

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

Determina se un Span<T> termina con un altro Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span da verificare |
| value | const [Span](../../system/span/)\<T\>\& | Lo span da verificare alla fine dello span di destinazione |

### Valore di ritorno

true se lo span termina con lo span valore, false altrimenti

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Determina se un ReadOnlySpan<char16_t> termina con il valore specificato usando StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span da verificare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Il valore da verificare alla fine dello span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Il tipo di confronto stringa da usare |

### Valore di ritorno

true se lo span termina con il valore, false altrimenti

## Vedi anche

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)