---
title: IndexOfAnyInRange()
second_title: Référence API Aspose.Slides pour C++
description: Recherche l'index du premier élément se trouvant dans la plage spécifiée dans un ReadOnlySpan<T>
type: docs
weight: 196
url: /fr/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Recherche l'index du premier élément qui se trouve dans la plage spécifiée dans un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type d'éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à parcourir |
| lowInclusive | const T\& | La borne inférieure de la plage (inclusive) |
| highInclusive | const T\& | La borne supérieure de la plage (inclusive) |

### Valeur de retour

L'index basé sur zéro du premier élément se trouvant dans la plage, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) fonction

Recherche l'index du premier élément qui se trouve dans la plage spécifiée dans un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type d'éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span à parcourir |
| lowInclusive | const T\& | La borne inférieure de la plage (inclusive) |
| highInclusive | const T\& | La borne supérieure de la plage (inclusive) |

### Valeur de retour

L'index basé sur zéro du premier élément se trouvant dans la plage, ou -1 s'il n'est pas trouvé

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)