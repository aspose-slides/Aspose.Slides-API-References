---
title: SequenceCompareTo()
second_title: Référence API Aspose.Slides pour C++
description: Compare deux ReadOnlySpans lexicographiquement.
type: docs
weight: 313
url: /fr/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Compare deux ReadOnlySpans lexicographiquement.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span à comparer |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le deuxième span à comparer |

### Valeur de retour

- 1 si span < other, 0 si span == other, 1 si span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Compare un [Span](../../system/span/) et [ReadOnlySpan](../../system/readonlyspan/) lexicographiquement.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) à comparer |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) à comparer |

### Valeur de retour

- 1 si span < other, 0 si span == other, 1 si span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) fonction

Compare un [ReadOnlySpan](../../system/readonlyspan/) et [Span](../../system/span/) lexicographiquement.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) à comparer |
| other | const [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) à comparer |

### Valeur de retour

- 1 si span < other, 0 si span == other, 1 si span > other

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)