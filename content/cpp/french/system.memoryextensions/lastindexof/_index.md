---
title: LastIndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche la dernière occurrence d'une séquence dans une plage.
type: docs
weight: 209
url: /fr/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Recherche la dernière occurrence d'une séquence dans une plage.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle rechercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence à rechercher |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si non trouvé

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Recherche la dernière occurrence d'une valeur unique dans une plage.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle rechercher |
| value | const T\& | La valeur à rechercher |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si non trouvé

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Recherche la dernière occurrence d'une séquence dans une plage mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage dans laquelle rechercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence à rechercher |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si non trouvé

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

Recherche la dernière occurrence d'une valeur unique dans une plage mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage dans laquelle rechercher |
| value | const T\& | La valeur à rechercher |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si non trouvé

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Recherche la dernière occurrence d'une valeur dans une plage en utilisant la comparaison de chaînes spécifiée.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La plage dans laquelle rechercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La valeur à rechercher |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Le type de comparaison de chaînes à effectuer |

### Valeur de retour

L'index basé sur zéro de la dernière occurrence, ou -1 si non trouvé

## Voir aussi

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)