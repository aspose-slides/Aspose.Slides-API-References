---
title: IndexOf()
second_title: Référence API Aspose.Slides pour C++
description: Trouve l'indice d'une valeur ReadOnlySpan<T> dans un autre ReadOnlySpan<T>
type: docs
weight: 144
url: /fr/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction


Trouve l'indice d'une valeur ReadOnlySpan<T> dans un autre ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à rechercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à rechercher |

### Valeur de retour

L'indice basé sur zéro de la première occurrence, ou -1 si non trouvé

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) fonction


Trouve l'indice d'une valeur unique dans un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à rechercher |
| value | const T\& | La valeur à rechercher |

### Valeur de retour

L'indice basé sur zéro de la première occurrence, ou -1 si non trouvé

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction


Trouve l'indice d'une valeur ReadOnlySpan<T> dans un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span à rechercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à rechercher |

### Valeur de retour

L'indice basé sur zéro de la première occurrence, ou -1 si non trouvé

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) fonction


Trouve l'indice d'une valeur unique dans un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span à rechercher |
| value | const T\& | La valeur à rechercher |

### Valeur de retour

L'indice basé sur zéro de la première occurrence, ou -1 si non trouvé

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonction


Trouve l'indice d'une valeur ReadOnlySpan<char16_t> dans un ReadOnlySpan<char16_t> avec StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Le span à rechercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La valeur à rechercher |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Le type de comparaison de chaîne à utiliser |

### Valeur de retour

L'indice basé sur zéro de la première occurrence, ou -1 si non trouvé

## Voir aussi

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)