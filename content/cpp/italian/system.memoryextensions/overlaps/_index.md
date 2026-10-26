---
title: Overlaps()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se due ReadOnlySpans si sovrappongono in memoria senza calcolare l'offset.
type: docs
weight: 274
url: /it/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Determina se due ReadOnlySpans si sovrappongono in memoria senza calcolare l'offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span da verificare per sovrapposizione |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span da verificare per sovrapposizione |

### Valore di ritorno

true se gli span condividono posizioni di memoria comuni, false altrimenti

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Determina se un [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) si sovrappongono in memoria senza calcolare l'offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il [Span](../../system/span/) da verificare per sovrapposizione |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il [ReadOnlySpan](../../system/readonlyspan/) da verificare per sovrapposizione |

### Valore di ritorno

true se gli span condividono posizioni di memoria comuni, false altrimenti

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funzione


Determina se due ReadOnlySpans si sovrappongono in memoria e calcola l'offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span da verificare per sovrapposizione |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span da verificare per sovrapposizione |
| elementOffset | **int32_t**\& | Parametro di output che riceve l'offset tra gli span se si sovrappongono |

### Valore di ritorno

true se gli span condividono posizioni di memoria comuni, false altrimenti

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funzione


Determina se un [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) si sovrappongono in memoria e calcola l'offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il [Span](../../system/span/) da verificare per sovrapposizione |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il [ReadOnlySpan](../../system/readonlyspan/) da verificare per sovrapposizione |
| elementOffset | **int32_t**\& | Parametro di output che riceve l'offset tra gli span se si sovrappongono |

### Valore di ritorno

true se gli span condividono posizioni di memoria comuni, false altrimenti

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)