---
title: LastIndexOfAnyInRange()
second_title: Référence API Aspose.Slides pour C++
description: Recherche la dernière occurrence de n'importe quel élément dans la plage spécifiée d'un span.
type: docs
weight: 261
url: /fr/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de n'importe quel élément dans la plage spécifiée d'un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
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

L'indice basé sur zéro du dernier élément de la plage, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de n'importe quel élément dans la plage spécifiée d'un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
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

L'indice basé sur zéro du dernier élément de la plage, ou -1 s'il n'est pas trouvé

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)