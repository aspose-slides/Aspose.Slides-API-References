---
title: ContainsAnyExcept()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si un span en lecture seule contient un élément autre que trois valeurs spécifiées.
type: docs
weight: 66
url: /fr/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Vérifie si un span en lecture seule contient un élément autre que trois valeurs spécifiées.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel rechercher |
| value0 | const T\& | Première valeur à exclure |
| value1 | const T\& | Deuxième valeur à exclure |
| value2 | const T\& | Troisième valeur à exclure |

### Valeur de retour

true si un élément différent des valeurs spécifiées est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Vérifie si un span mutable contient un élément autre que trois valeurs spécifiées.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable dans lequel rechercher |
| value0 | const T\& | Première valeur à exclure |
| value1 | const T\& | Deuxième valeur à exclure |
| value2 | const T\& | Troisième valeur à exclure |

### Valeur de retour

true si un élément différent des valeurs spécifiées est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Vérifie si un span en lecture seule contient un élément autre que deux valeurs spécifiées.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel rechercher |
| value0 | const T\& | Première valeur à exclure |
| value1 | const T\& | Deuxième valeur à exclure |

### Valeur de retour

true si un élément différent des valeurs spécifiées est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Vérifie si un span mutable contient un élément autre que deux valeurs spécifiées.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable dans lequel rechercher |
| value0 | const T\& | Première valeur à exclure |
| value1 | const T\& | Deuxième valeur à exclure |

### Valeur de retour

true si un élément différent des valeurs spécifiées est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Vérifie si un span en lecture seule contient un élément autre qu'une valeur spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel rechercher |
| value | const T\& | Valeur à exclure |

### Valeur de retour

true si un élément différent de la valeur spécifiée est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function

Vérifie si un span mutable contient un élément autre qu'une valeur spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable dans lequel rechercher |
| value | const T\& | Valeur à exclure |

### Valeur de retour

true si un élément différent de la valeur spécifiée est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Vérifie si un span en lecture seule contient un élément autre que ceux d'un autre span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments des spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span dans lequel rechercher |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span des valeurs à exclure |

### Valeur de retour

true si un élément différent des valeurs spécifiées est trouvé, false sinon

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Vérifie si un span mutable contient un élément autre que ceux d'un span en lecture seule.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments des spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable dans lequel rechercher |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span en lecture seule des valeurs à exclure |

### Valeur de retour

true si un élément différent des valeurs spécifiées est trouvé, false sinon

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)