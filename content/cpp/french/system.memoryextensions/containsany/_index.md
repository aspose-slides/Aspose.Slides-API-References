---
title: ContainsAny()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si une plage en lecture seule contient l'une des deux valeurs.
type: docs
weight: 53
url: /fr/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonction

Vérifie si une plage en lecture seule contient l'une des deux valeurs.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle rechercher |
| value0 | const T\& | La première valeur à rechercher |
| value1 | const T\& | La deuxième valeur à rechercher |

### Valeur de retour

true si l'une des valeurs est trouvée dans la plage, false sinon

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) fonction

Vérifie si une plage en lecture seule contient l'une des trois valeurs.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle rechercher |
| value0 | const T\& | La première valeur à rechercher |
| value1 | const T\& | La deuxième valeur à rechercher |
| value2 | const T\& | La troisième valeur à rechercher |

### Valeur de retour

true si l'une des valeurs est trouvée dans la plage, false sinon

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) fonction

Vérifie si une plage mutable contient l'une des deux valeurs.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage mutable dans laquelle rechercher |
| value0 | const T\& | La première valeur à rechercher |
| value1 | const T\& | La deuxième valeur à rechercher |

### Valeur de retour

true si l'une des valeurs est trouvée dans la plage, false sinon

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) fonction

Vérifie si une plage mutable contient l'une des trois valeurs.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage mutable dans laquelle rechercher |
| value0 | const T\& | La première valeur à rechercher |
| value1 | const T\& | La deuxième valeur à rechercher |
| value2 | const T\& | La troisième valeur à rechercher |

### Valeur de retour

true si l'une des valeurs est trouvée dans la plage, false sinon

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Vérifie si une plage en lecture seule contient une valeur quelconque d'une autre plage.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle rechercher |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage de valeurs à rechercher |

### Valeur de retour

true si une valeur de values est trouvée dans span, false sinon

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Vérifie si une plage mutable contient une valeur quelconque d'une plage en lecture seule.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage mutable dans laquelle rechercher |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage en lecture seule de valeurs à rechercher |

### Valeur de retour

true si une valeur de values est trouvée dans span, false sinon

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)