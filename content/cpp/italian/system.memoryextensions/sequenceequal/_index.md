---
title: SequenceEqual()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se due ReadOnlySpan contengono elementi identici nello stesso ordine.
type: docs
weight: 326
url: /it/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determina se due ReadOnlySpan contengono elementi identici nello stesso ordine.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span da confrontare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span da confrontare |

### Valore restituito

true se gli span hanno la stessa lunghezza e tutti gli elementi sono uguali, false altrimenti

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determina se un [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) contengono elementi identici nello stesso ordine.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il [Span](../../system/span/) da confrontare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il [ReadOnlySpan](../../system/readonlyspan/) da confrontare |

### Valore restituito

true se gli span hanno la stessa lunghezza e tutti gli elementi sono uguali, false altrimenti

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function


Determina se due ReadOnlySpan contengono elementi uguali usando un comparatore personalizzato.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |
| TComparer | Il tipo dell'oggetto comparatore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span da confrontare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span da confrontare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntatore intelligente all'oggetto comparatore per il confronto degli elementi |

### Valore restituito

true se gli span hanno la stessa lunghezza e il comparatore considera tutti gli elementi uguali, false altrimenti

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function


Determina se un [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) contengono elementi uguali usando un comparatore personalizzato.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |
| TComparer | Il tipo dell'oggetto comparatore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il [Span](../../system/span/) da confrontare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il [ReadOnlySpan](../../system/readonlyspan/) da confrontare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntatore intelligente all'oggetto comparatore per il confronto degli elementi |

### Valore restituito

true se gli span hanno la stessa lunghezza e il comparatore considera tutti gli elementi uguali, false altrimenti

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)