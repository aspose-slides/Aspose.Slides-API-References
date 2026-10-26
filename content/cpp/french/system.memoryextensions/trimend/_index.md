---
title: TrimEnd()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime l'élément spécifié de la fin d'une span typée.
type: docs
weight: 378
url: /fr/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function

Supprime l'élément spécifié de la fin d'une span typée.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La span à tronquer |
| trimElement | const T\& | L'élément à tronquer |

### Valeur de retour

Une nouvelle span avec l'élément spécifié supprimé de la fin

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function

Supprime l'élément spécifié de la fin d'une span typée mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | La span mutable à tronquer |
| trimElement | const T\& | L'élément à tronquer |

### Valeur de retour

Une nouvelle span avec l'élément spécifié supprimé de la fin

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Supprime les éléments spécifiés de la fin d'une span typée.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La span à tronquer |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Les éléments à tronquer |

### Valeur de retour

Une nouvelle span avec les éléments spécifiés supprimés de la fin

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Supprime les éléments spécifiés de la fin d'une span typée mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | La span mutable à tronquer |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Les éléments à tronquer |

### Valeur de retour

Une nouvelle span avec les éléments spécifiés supprimés de la fin

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function

Supprime les caractères d'espace blanc de la fin d'une span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La span de caractères à tronquer |

### Valeur de retour

Une nouvelle span avec les caractères d'espace blanc supprimés de la fin

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function

Supprime les caractères d'espace blanc de la fin d'une span de caractères mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | La span de caractères mutable à tronquer |

### Valeur de retour

Une nouvelle span avec les caractères d'espace blanc supprimés de la fin

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function

Supprime le caractère spécifié de la fin d'une span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La span de caractères à tronquer |
| trimchar | char16_t | Le caractère à tronquer |

### Valeur de retour

Une nouvelle span avec le caractère spécifié supprimé de la fin

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function

Supprime le caractère spécifié de la fin d'une span de caractères mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | La span de caractères mutable à tronquer |
| trimchar | char16_t | Le caractère à tronquer |

### Valeur de retour

Une nouvelle span avec le caractère spécifié supprimé de la fin

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Supprime les caractères spécifiés de la fin d'une span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La span de caractères à tronquer |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Les caractères à tronquer |

### Valeur de retour

Une nouvelle span avec les caractères spécifiés supprimés de la fin

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Supprime les caractères spécifiés de la fin d'une span de caractères mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | La span de caractères mutable à tronquer |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Les caractères à tronquer |

### Valeur de retour

Une nouvelle span avec les caractères spécifiés supprimés de la fin

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)