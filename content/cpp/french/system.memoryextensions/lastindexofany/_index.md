---
title: LastIndexOfAny()
second_title: Référence API Aspose.Slides pour C++
description: Recherche la dernière occurrence de l'une des trois valeurs spécifiées dans un span.
type: docs
weight: 222
url: /fr/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Recherche la dernière occurrence de l'une des trois valeurs spécifiées dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Recherche la dernière occurrence de l'une des trois valeurs spécifiées dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Recherche la dernière occurrence de l'une des deux valeurs spécifiées dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

Recherche la dernière occurrence de l'une des deux valeurs spécifiées dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Recherche la dernière occurrence de n'importe quelle valeur d'une séquence dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Recherche la dernière occurrence de n'importe quelle valeur d'une séquence dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) function

Recherche la dernière occurrence de n'importe quelle valeur d'une séquence mutable dans un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to search for |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si aucune correspondance n'est trouvée

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)