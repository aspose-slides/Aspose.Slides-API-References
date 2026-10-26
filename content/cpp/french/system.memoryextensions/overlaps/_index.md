---
title: Overlaps()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si deux ReadOnlySpans se chevauchent en mémoire sans calculer le décalage.
type: docs
weight: 274
url: /fr/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Détermine si deux ReadOnlySpans se chevauchent en mémoire sans calculer le décalage.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span à vérifier le chevauchement |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le second span à vérifier le chevauchement |

### Valeur de retour

true si les spans partagent des emplacements mémoire communs, false sinon

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Détermine si un [Span](../../system/span/) et [ReadOnlySpan](../../system/readonlyspan/) se chevauchent en mémoire sans calculer le décalage.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) à vérifier le chevauchement |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) à vérifier le chevauchement |

### Valeur de retour

true si les spans partagent des emplacements mémoire communs, false sinon

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) fonction

Détermine si deux ReadOnlySpans se chevauchent en mémoire et calcule le décalage.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span à vérifier le chevauchement |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le second span à vérifier le chevauchement |
| elementOffset | **int32_t**\& | Paramètre de sortie qui reçoit le décalage entre les spans s'ils se chevauchent |

### Valeur de retour

true si les spans partagent des emplacements mémoire communs, false sinon

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) fonction

Détermine si un [Span](../../system/span/) et [ReadOnlySpan](../../system/readonlyspan/) se chevauchent en mémoire et calcule le décalage.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) à vérifier le chevauchement |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) à vérifier le chevauchement |
| elementOffset | **int32_t**\& | Paramètre de sortie qui reçoit le décalage entre les spans s'ils se chevauchent |

### Valeur de retour

true si les spans partagent des emplacements mémoire communs, false sinon

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)