---
title: LastIndexOf()
second_title: Riferimento API Aspose.Slides per C++
description: Trova l'ultima occorrenza di una sequenza all'interno di uno span.
type: docs
weight: 209
url: /it/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Trova l'ultima occorrenza di una sequenza all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La sequenza da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, oppure -1 se non trovata

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Trova l'ultima occorrenza di un singolo valore all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value | const T\& | Il valore da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, oppure -1 se non trovata

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Trova l'ultima occorrenza di una sequenza all'interno di uno span mutabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La sequenza da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, oppure -1 se non trovata

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

Trova l'ultima occorrenza di un singolo valore all'interno di uno span mutabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| value | const T\& | Il valore da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, oppure -1 se non trovata

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Trova l'ultima occorrenza di un valore all'interno di uno span utilizzando il confronto di stringhe specificato.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span in cui cercare |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Il valore da cercare |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Il tipo di confronto di stringhe da eseguire |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, oppure -1 se non trovata

## Vedi anche

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)