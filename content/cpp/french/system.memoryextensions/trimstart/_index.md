---
title: TrimStart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime l'élément spécifié du début d'un span typé.
type: docs
weight: 391
url: /fr/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) fonction

Supprime l'élément spécifié du début d'un span typé.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | const T\& | The element to trim |

### Valeur de retour

A new span with the specified element trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) fonction

Supprime l'élément spécifié du début d'un span typé mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | const T\& | The element to trim |

### Valeur de retour

A new span with the specified element trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Supprime les éléments spécifiés du début d'un span typé.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Valeur de retour

A new span with the specified elements trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Supprime les éléments spécifiés du début d'un span typé mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Valeur de retour

A new span with the specified elements trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) fonction

Supprime les caractères d'espacement du début d'un span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |

### Valeur de retour

A new span with whitespace trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) fonction

Supprime les caractères d'espacement du début d'un span de caractères mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |

### Valeur de retour

A new span with whitespace trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) fonction

Supprime le caractère spécifié du début d'un span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |
| trimchar | char16_t | The character to trim |

### Valeur de retour

A new span with the specified character trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) fonction

Supprime le caractère spécifié du début d'un span de caractères mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |
| trimchar | char16_t | The character to trim |

### Valeur de retour

A new span with the specified character trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) fonction

Supprime les caractères spécifiés du début d'un span de caractères.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The characters to trim |

### Valeur de retour

A new span with the specified characters trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) fonction

Supprime les caractères spécifiés du début d'un span de caractères mutable.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The characters to trim |

### Valeur de retour

A new span with the specified characters trimmed from the start

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)