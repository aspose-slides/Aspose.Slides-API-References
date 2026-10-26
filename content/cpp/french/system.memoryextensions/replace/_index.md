---
title: Replace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace toutes les occurrences d'une valeur par une nouvelle valeur dans un Span.
type: docs
weight: 287
url: /fr/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) fonction


Remplace toutes les occurrences d'une valeur par une nouvelle valeur dans un [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Le span à modifier en place |
| oldValue | const T\& | La valeur à rechercher et remplacer |
| newValue | const T\& | La nouvelle valeur qui remplace oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) fonction


Copie les éléments de la source vers la destination, en remplaçant les valeurs spécifiées pendant la copie.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) source dont il faut copier |
| destination | [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) de destination vers lequel copier |
| oldValue | const T\& | La valeur à rechercher et remplacer lors de la copie |
| newValue | const T\& | La nouvelle valeur qui remplace oldValue avec |

## Voir aussi

* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)