---
title: StartsWith()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se lo span inizia con il valore specificato.
type: docs
weight: 352
url: /it/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) funzione

Verifica se lo span inizia con il valore specificato.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare |
| value | const T\& | Il valore da verificare all'inizio dello span |

### Valore restituito

true se lo span inizia con il valore, false altrimenti

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Verifica se lo span inizia con lo span di valore specificato.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da verificare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span contenente i valori da verificare all'inizio |

### Valore restituito

true se lo span inizia con lo span di valore, false altrimenti

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Verifica se lo span modificabile inizia con lo span di valore di sola lettura specificato.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile da verificare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di sola lettura contenente i valori da verificare |

### Valore restituito

true se lo span inizia con lo span di valore, false altrimenti

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funzione

Verifica se lo span di sola lettura inizia con lo span di valore modificabile specificato.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di sola lettura da verificare |
| value | const [Span](../../system/span/)\<T\>\& | Lo span modificabile contenente i valori da verificare |

### Valore restituito

true se lo span inizia con lo span di valore, false altrimenti

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funzione

Verifica se lo span di caratteri inizia con lo span di valore specificato usando il confronto di stringhe.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da verificare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri contenente i valori da verificare |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Il tipo di confronto di stringhe da eseguire |

### Valore restituito

true se lo span inizia con lo span di valore, false altrimenti

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) funzione

Verifica se un span di stringhe inizia con l'array di caratteri specificato.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Lo span di stringhe da verificare |
| val | const char16_t * | L'array di caratteri da verificare all'inizio |

### Valore restituito

true se lo span inizia con l'array di caratteri, false altrimenti

## Vedi anche

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Classe [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)