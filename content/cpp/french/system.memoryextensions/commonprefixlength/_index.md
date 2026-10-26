---
title: CommonPrefixLength()
second_title: Référence API Aspose.Slides pour C++
description: Trouve la longueur du préfixe commun entre deux spans.
type: docs
weight: 27
url: /fr/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonction


Trouve la longueur du préfixe commun entre deux spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le second span |

### Valeur de retour

Le nombre d’éléments correspondants au début des deux spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonction


Trouve la longueur du préfixe commun entre un span mutable et un span en lecture seule.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span en lecture seule |

### Valeur de retour

Le nombre d’éléments correspondants au début des deux spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) fonction


Trouve la longueur du préfixe commun entre deux spans mutables.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le premier span mutable |
| other | const [Span](../../system/span/)\<T\>\& | Le second span mutable |

### Valeur de retour

Le nombre d’éléments correspondants au début des deux spans

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) fonction


Trouve la longueur du préfixe commun entre deux spans en utilisant un comparateur d’égalité personnalisé.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |
| TEqualityComparer | Le type du comparateur d’égalité |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le premier span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le second span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Le comparateur d’égalité à utiliser pour la comparaison des éléments |

### Valeur de retour

Le nombre d’éléments correspondants au début des deux spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) fonction


Trouve la longueur du préfixe commun entre un span mutable et un span en lecture seule en utilisant un comparateur d’égalité personnalisé.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |
| TEqualityComparer | Le type du comparateur d’égalité |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span mutable |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span en lecture seule |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Le comparateur d’égalité à utiliser pour la comparaison des éléments |

### Valeur de retour

Le nombre d’éléments correspondants au début des deux spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) fonction


Trouve la longueur du préfixe commun entre deux spans mutables en utilisant un comparateur d’égalité personnalisé.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans les spans |
| TEqualityComparer | Le type du comparateur d’égalité |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le premier span mutable |
| other | const [Span](../../system/span/)\<T\>\& | Le second span mutable |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Le comparateur d’égalité à utiliser pour la comparaison des éléments |

### Valeur de retour

Le nombre d’éléments correspondants au début des deux spans

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)