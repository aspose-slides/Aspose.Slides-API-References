---
title: LastIndexOfAnyExcept()
second_title: Référence API Aspose.Slides pour C++
description: Recherche la dernière occurrence de tout élément, sauf trois valeurs spécifiées, dans un span.
type: docs
weight: 235
url: /fr/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de tout élément, sauf les trois valeurs spécifiées, dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel chercher |
| value0 | const T\& | La première valeur à exclure |
| value1 | const T\& | La seconde valeur à exclure |
| value2 | const T\& | La troisième valeur à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de tout élément, sauf les trois valeurs spécifiées, dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span dans lequel chercher |
| value0 | const T\& | La première valeur à exclure |
| value1 | const T\& | La seconde valeur à exclure |
| value2 | const T\& | La troisième valeur à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de tout élément, sauf les deux valeurs spécifiées, dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel chercher |
| value0 | const T\& | La première valeur à exclure |
| value1 | const T\& | La seconde valeur à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) fonction

Recherche la dernière occurrence de tout élément, sauf les deux valeurs spécifiées, dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span dans lequel chercher |
| value0 | const T\& | La première valeur à exclure |
| value1 | const T\& | La seconde valeur à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) fonction

Recherche la dernière occurrence de tout élément, sauf la valeur spécifiée, dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel chercher |
| value | const T\& | La valeur à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) fonction

Recherche la dernière occurrence de tout élément, sauf la valeur spécifiée, dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span dans lequel chercher |
| value | const T\& | La valeur à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Recherche la dernière occurrence de tout élément, sauf les valeurs provenant d'une séquence, dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel chercher |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence de valeurs à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Recherche la dernière occurrence de tout élément, sauf les valeurs provenant d'une séquence, dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span dans lequel chercher |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence de valeurs à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) fonction

Recherche la dernière occurrence de tout élément, sauf les valeurs provenant d'une séquence mutable, dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span dans lequel chercher |
| values | const [Span](../../system/span/)\<T\>\& | La séquence de valeurs à exclure |

### Valeur de retour

L'index basé sur zéro du dernier élément non exclu, ou -1 s'il n'est pas trouvé

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)