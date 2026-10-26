---
title: SequenceEqual()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si deux ReadOnlySpan contiennent des éléments identiques dans le même ordre.
type: docs
weight: 326
url: /fr/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Détermine si deux ReadOnlySpan contiennent des éléments identiques dans le même ordre.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span à comparer |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le second span à comparer |

### Valeur de retour

true si les spans ont la même longueur et que tous les éléments sont égaux, false sinon

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction

Détermine si un [Span](../../system/span/) et [ReadOnlySpan](../../system/readonlyspan/) contiennent des éléments identiques dans le même ordre.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) à comparer |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) à comparer |

### Valeur de retour

true si les spans ont la même longueur et que tous les éléments sont égaux, false sinon

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) fonction

Détermine si deux ReadOnlySpan contiennent des éléments égaux en utilisant un comparateur personnalisé.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |
| TComparer | Le type de l'objet comparateur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span à comparer |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le second span à comparer |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Pointeur intelligent vers l'objet comparateur pour la comparaison des éléments |

### Valeur de retour

true si les spans ont la même longueur et que le comparateur considère tous les éléments comme égaux, false sinon

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) fonction

Détermine si un [Span](../../system/span/) et [ReadOnlySpan](../../system/readonlyspan/) contiennent des éléments égaux en utilisant un comparateur personnalisé.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |
| TComparer | Le type de l'objet comparateur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le [Span](../../system/span/) à comparer |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le [ReadOnlySpan](../../system/readonlyspan/) à comparer |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Pointeur intelligent vers l'objet comparateur pour la comparaison des éléments |

### Valeur de retour

true si les spans ont la même longueur et que le comparateur considère tous les éléments comme égaux, false sinon

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)