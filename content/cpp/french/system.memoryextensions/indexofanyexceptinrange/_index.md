---
title: IndexOfAnyExceptInRange()
second_title: Référence API Aspose.Slides pour C++
description: Trouve l'index du premier élément qui se trouve en dehors de la plage spécifiée dans un ReadOnlySpan<T>
type: docs
weight: 183
url: /fr/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Trouve l'index du premier élément qui se trouve en dehors de la plage spécifiée dans un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel chercher |
| lowInclusive | const T\& | La borne inférieure de la plage (incluse) |
| highInclusive | const T\& | La borne supérieure de la plage (incluse) |

### Valeur de retour

L'index basé sur zéro du premier élément hors de la plage, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fonction

Trouve l'index du premier élément qui se trouve en dehors de la plage spécifiée dans un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span dans lequel chercher |
| lowInclusive | const T\& | La borne inférieure de la plage (incluse) |
| highInclusive | const T\& | La borne supérieure de la plage (incluse) |

### Valeur de retour

L'index basé sur zéro du premier élément hors de la plage, ou -1 s'il n'est pas trouvé

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)