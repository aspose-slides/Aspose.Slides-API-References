---
title: Contains()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se uno span di sola lettura contiene un valore specifico.
type: docs
weight: 40
url: /it/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) function

Verifica se uno span di sola lettura contiene un valore specifico.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value | const T\& | Il valore da cercare |

### Valore restituito

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) function

Verifica se uno span mutabile contiene un valore specifico.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span mutabile in cui cercare |
| value | const T\& | Il valore da cercare |

### Valore restituito

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Verifica se uno span di caratteri contiene un altro span di caratteri con regole di confronto specificate.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span in cui cercare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span da cercare |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Il tipo di confronto di stringa da eseguire |

### Valore restituito

true if value is found in span, false otherwise

## Vedi anche

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)