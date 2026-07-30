---
title: CommonPrefixLength()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova la lunghezza del prefisso comune tra due span.
type: docs
weight: 27
url: /it/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Trova la lunghezza del prefisso comune tra due span.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span |

### Valore restituito

Il numero di elementi corrispondenti all'inizio di entrambi gli span

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Trova la lunghezza del prefisso comune tra uno span mutabile e uno span di sola lettura.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span mutabile |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di sola lettura |

### Valore restituito

Il numero di elementi corrispondenti all'inizio di entrambi gli span

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) funzione


Trova la lunghezza del prefisso comune tra due span mutabili.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il primo span mutabile |
| other | const [Span](../../system/span/)\<T\>\& | Il secondo span mutabile |

### Valore restituito

Il numero di elementi corrispondenti all'inizio di entrambi gli span

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funzione


Trova la lunghezza del prefisso comune tra due span usando un comparatore di uguaglianza personalizzato.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |
| TEqualityComparer | Il tipo del comparatore di uguaglianza |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Il comparatore di uguaglianza da usare per il confronto degli elementi |

### Valore restituito

Il numero di elementi corrispondenti all'inizio di entrambi gli span

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funzione


Trova la lunghezza del prefisso comune tra uno span mutabile e uno span di sola lettura usando un comparatore di uguaglianza personalizzato.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |
| TEqualityComparer | Il tipo del comparatore di uguaglianza |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span mutabile |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di sola lettura |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Il comparatore di uguaglianza da usare per il confronto degli elementi |

### Valore restituito

Il numero di elementi corrispondenti all'inizio di entrambi gli span

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funzione


Trova la lunghezza del prefisso comune tra due span mutabili usando un comparatore di uguaglianza personalizzato.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |
| TEqualityComparer | Il tipo del comparatore di uguaglianza |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il primo span mutabile |
| other | const [Span](../../system/span/)\<T\>\& | Il secondo span mutabile |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Il comparatore di uguaglianza da usare per il confronto degli elementi |

### Valore restituito

Il numero di elementi corrispondenti all'inizio di entrambi gli span

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)