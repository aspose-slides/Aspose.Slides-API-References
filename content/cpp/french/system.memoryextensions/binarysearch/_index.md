---
title: BinarySearch()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue une recherche binaire sur un span trié.
type: docs
weight: 14
url: /fr/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) fonction

Effectue une recherche binaire sur un span trié.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type d'éléments du span |
| TComparable | Le type de la valeur comparable |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span trié à rechercher |
| comparable | const TComparable\& | La valeur à rechercher |

### Valeur de retour

Indice de l'élément trouvé, ou complément à un bit du point d'insertion si non trouvé

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) fonction

Effectue une recherche binaire sur un span trié en utilisant un comparateur personnalisé.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type d'éléments du span |
| TComparer | Le type du comparateur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span trié à rechercher |
| value | const T\& | La valeur à rechercher |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Le comparateur à utiliser pour les comparaisons |

### Valeur de retour

Indice de l'élément trouvé, ou complément à un bit du point d'insertion si non trouvé

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) fonction

Effectue une recherche binaire sur un span mutable trié.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type d'éléments du span |
| TComparable | Le type de la valeur comparable |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span trié à rechercher |
| comparable | const TComparable\& | La valeur à rechercher |

### Valeur de retour

Indice de l'élément trouvé, ou complément à un bit du point d'insertion si non trouvé

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) fonction

Effectue une recherche binaire sur un span mutable trié en utilisant un comparateur personnalisé.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type d'éléments du span |
| TComparer | Le type du comparateur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span trié à rechercher |
| value | const T\& | La valeur à rechercher |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Le comparateur à utiliser pour les comparaisons |

### Valeur de retour

Indice de l'élément trouvé, ou complément à un bit du point d'insertion si non trouvé

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)