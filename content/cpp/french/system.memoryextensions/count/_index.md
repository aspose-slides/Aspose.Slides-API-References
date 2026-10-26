---
title: Count()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compte le nombre d'occurrences d'une valeur dans une plage en lecture seule.
type: docs
weight: 118
url: /fr/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) fonction

Compte le nombre d'occurrences d'une valeur dans une plage en lecture seule.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle chercher |
| value | const T\& | La valeur à compter |

### Valeur de retour

Le nombre de fois où la valeur apparaît dans la plage

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Compte le nombre d'occurrences d'une plage dans une autre plage en lecture seule.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle chercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dont on compte les occurrences |

### Valeur de retour

Le nombre de fois où la plage apparaît dans la plage

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) fonction

Compte le nombre d'occurrences d'une valeur unique dans un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage dans laquelle chercher |
| value | const T\& | La valeur dont on compte les occurrences |

### Valeur de retour

Le nombre d'occurrences de la valeur dans la plage

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Compte le nombre d'occurrences d'un ReadOnlySpan<T> dans un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage dans laquelle chercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage contenant les valeurs dont on compte les occurrences |

### Valeur de retour

Le nombre d'occurrences de la plage de valeurs dans la plage cible

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)