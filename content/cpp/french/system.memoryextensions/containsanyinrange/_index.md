---
title: ContainsAnyInRange()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si un span en lecture seule contient un élément quelconque dans la plage spécifiée.
type: docs
weight: 92
url: /fr/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Vérifie si un span en lecture seule contient un élément quelconque dans la plage spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span (doit être comparable) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel rechercher |
| lowInclusive | const T\& | La borne inférieure (incluse) |
| highInclusive | const T\& | La borne supérieure (incluse) |

### Valeur de retour

true si un élément quelconque dans la plage est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) fonction

Vérifie si un span mutable contient un élément quelconque dans la plage spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span (doit être comparable) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable dans lequel rechercher |
| lowInclusive | const T\& | La borne inférieure (incluse) |
| highInclusive | const T\& | La borne supérieure (incluse) |

### Valeur de retour

true si un élément quelconque dans la plage est trouvé, false sinon

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)