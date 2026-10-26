---
title: BinarySearch()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue una ricerca binaria su uno span ordinato.
type: docs
weight: 14
url: /it/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) funzione

Esegue una ricerca binaria su uno span ordinato.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |
| TComparable | Il tipo del valore comparabile |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span ordinato da cercare |
| comparable | const TComparable\& | Il valore da cercare |

### Valore di ritorno

[Index](../../system/index/) dell'elemento trovato, o complemento bitwise del punto di inserimento se non trovato

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) funzione

Esegue una ricerca binaria su uno span ordinato usando un comparatore personalizzato.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |
| TComparer | Il tipo del comparatore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span ordinato da cercare |
| value | const T\& | Il valore da cercare |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Il comparatore da utilizzare per le comparazioni |

### Valore di ritorno

[Index](../../system/index/) dell'elemento trovato, o complemento bitwise del punto di inserimento se non trovato

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) funzione

Esegue una ricerca binaria su uno span ordinato mutabile.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |
| TComparable | Il tipo del valore comparabile |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span ordinato da cercare |
| comparable | const TComparable\& | Il valore da cercare |

### Valore di ritorno

[Index](../../system/index/) dell'elemento trovato, o complemento bitwise del punto di inserimento se non trovato

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) funzione

Esegue una ricerca binaria su uno span ordinato mutabile usando un comparatore personalizzato.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |
| TComparer | Il tipo del comparatore |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span ordinato da cercare |
| value | const T\& | Il valore da cercare |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Il comparatore da utilizzare per le comparazioni |

### Valore di ritorno

[Index](../../system/index/) dell'elemento trovato, o complemento bitwise del punto di inserimento se non trovato

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)