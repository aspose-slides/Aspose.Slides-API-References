---
title: Trim()
second_title: Référence API Aspose.Slides pour C++
description: Supprime l'élément spécifié des deux extrémités d'un span typé.
type: docs
weight: 365
url: /fr/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) function

Supprime l'élément spécifié des deux extrémités d'un span typé.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à tronquer |
| trimElement | T | L'élément à tronquer |

### Valeur de retour

Un nouveau span avec l'élément spécifié tronqué des deux extrémités

## System::MemoryExtensions::Trim(Span\<T\>\&, T) function

Supprime l'élément spécifié des deux extrémités d'un span mutable typé.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Le span mutable à tronquer |
| trimElement | T | L'élément à tronquer |

### Valeur de retour

Un nouveau span avec l'élément spécifié tronqué des deux extrémités

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Supprime les éléments spécifiés des deux extrémités d'un span typé.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à tronquer |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Les éléments à tronquer |

### Valeur de retour

Un nouveau span avec les éléments spécifiés tronqués des deux extrémités

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Supprime les éléments spécifiés des deux extrémités d'un span mutable typé.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Le span mutable à tronquer |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Les éléments à tronquer |

### Valeur de retour

Un nouveau span avec les éléments spécifiés tronqués des deux extrémités

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) function

Supprime les caractères d'espaces blancs des deux extrémités d'un span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Le span de caractères à tronquer |

### Valeur de retour

Un nouveau span avec les espaces blancs tronqués des deux extrémités

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) function

Supprime les caractères d'espaces blancs des deux extrémités d'un span mutable de caractères.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Le span mutable de caractères à tronquer |

### Valeur de retour

Un nouveau span avec les espaces blancs tronqués des deux extrémités

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)