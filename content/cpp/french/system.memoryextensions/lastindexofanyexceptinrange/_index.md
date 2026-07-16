---
title: LastIndexOfAnyExceptInRange()
second_title: Référence API Aspose.Slides pour C++
description: Recherche la dernière occurrence de tout élément en dehors de la plage spécifiée dans une étendue.
type: docs
weight: 248
url: /fr/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de tout élément en dehors de la plage spécifiée dans une étendue.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### Valeur de retour

L'indice basé sur zéro du dernier élément hors de la plage, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de tout élément en dehors de la plage spécifiée dans une étendue mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### Valeur de retour

L'indice basé sur zéro du dernier élément hors de la plage, ou -1 s'il n'est pas trouvé

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)