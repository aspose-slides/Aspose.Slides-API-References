---
title: IndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'indice di un valore ReadOnlySpan<T> in un altro ReadOnlySpan<T>
type: docs
weight: 144
url: /it/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Trova l'indice di un valore ReadOnlySpan<T> in un altro ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### Valore di ritorno

L'indice basato su zero della prima occorrenza, o -1 se non trovato

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Trova l'indice di un singolo valore in un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Valore di ritorno

L'indice basato su zero della prima occorrenza, o -1 se non trovato

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Trova l'indice di un valore ReadOnlySpan<T> in un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### Valore di ritorno

L'indice basato su zero della prima occorrenza, o -1 se non trovato

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) function

Trova l'indice di un singolo valore in un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Valore di ritorno

L'indice basato su zero della prima occorrenza, o -1 se non trovato

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Trova l'indice di un valore ReadOnlySpan<char16_t> in un ReadOnlySpan<char16_t> con StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Il tipo di confronto stringa da utilizzare |

### Valore di ritorno

L'indice basato su zero della prima occorrenza, o -1 se non trovato

## Vedi anche

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)