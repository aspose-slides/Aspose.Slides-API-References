---
title: ContainsAnyExceptInRange()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si un span en lecture seule contient tout élément en dehors de la plage spécifiée.
type: docs
weight: 79
url: /fr/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction


Vérifie si un span en lecture seule contient tout élément en dehors de la plage spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span (must be comparable) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound (inclusive) |
| highInclusive | const T\& | The upper bound (inclusive) |

### Valeur de retour

true if any element outside the range is found, false otherwise

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fonction


Vérifie si un span mutable contient tout élément en dehors de la plage spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span (must be comparable) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| lowInclusive | const T\& | The lower bound (inclusive) |
| highInclusive | const T\& | The upper bound (inclusive) |

### Valeur de retour

true if any element outside the range is found, false otherwise

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)