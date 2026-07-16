---
title: EndsWith()
second_title: Référence API Aspose.Slides for C++
description: Détermine si un ReadOnlySpan<T> se termine par une valeur unique.
type: docs
weight: 131
url: /fr/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

Détermine si un ReadOnlySpan<T> se termine par une valeur unique.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage à vérifier |
| value | const T\& | La valeur à vérifier à la fin de la plage |

### Valeur de retour

true si la plage se termine par la valeur, false sinon

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Détermine si un ReadOnlySpan<T> se termine par un autre ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage à vérifier |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage à vérifier à la fin de la plage cible |

### Valeur de retour

true si la plage se termine par la valeur de la plage, false sinon

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Détermine si un Span<T> se termine par un ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage à vérifier |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage à vérifier à la fin de la plage cible |

### Valeur de retour

true si la plage se termine par la valeur de la plage, false sinon

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

Détermine si un ReadOnlySpan<T> se termine par un Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage à vérifier |
| value | const [Span](../../system/span/)\<T\>\& | La plage à vérifier à la fin de la plage cible |

### Valeur de retour

true si la plage se termine par la valeur de la plage, false sinon

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

Détermine si un Span<T) se termine par un autre Span<T)

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les plages |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage à vérifier |
| value | const [Span](../../system/span/)\<T\>\& | La plage à vérifier à la fin de la plage cible |

### Valeur de retour

true si la plage se termine par la valeur de la plage, false sinon

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Détermine si un ReadOnlySpan<char16_t> se termine par la valeur spécifiée en utilisant StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La plage à vérifier |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La valeur à vérifier à la fin de la plage |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Le type de comparaison de chaîne à utiliser |

### Valeur de retour

true si la plage se termine par la valeur, false sinon

## Voir aussi

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)