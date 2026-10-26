---
title: Sort()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trie un Span en utilisant un comparateur personnalisé.
type: docs
weight: 339
url: /fr/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) fonction

Trie un [Span](../../system/span/) en utilisant un comparateur personnalisé.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span |
| TComparer | Le type de l'objet comparateur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Le span à trier |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Pointeur intelligent vers l'objet comparateur pour la comparaison des éléments |

## System::MemoryExtensions::Sort(Span\<T\>\&) fonction

Trie un [Span](../../system/span/) en utilisant la comparaison par défaut.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Le span à trier |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) fonction

Trie des paires clé-valeur en utilisant un comparateur personnalisé (clés et valeurs triées ensemble)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |
| TComparer | Le type de l'objet comparateur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Le span de clés à trier |
| values | [Span](../../system/span/)\<TValue\>\& | Le span de valeurs à trier (en maintenant la correspondance avec les clés) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Pointeur intelligent vers l'objet comparateur pour la comparaison des clés |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) fonction

Trie des paires clé-valeur en utilisant un délégué de comparaison.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Le span de clés à trier |
| values | [Span](../../system/span/)\<TValue\>\& | Le span de valeurs à trier |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | délégué [Comparison](../../system/comparison/) pour la comparaison des clés |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) fonction

Trie des paires clé-valeur en utilisant la comparaison par défaut.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Le span de clés à trier |
| values | [Span](../../system/span/)\<TValue\>\& | Le span de valeurs à trier |

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Span](../../system/span/)
* Class [Comparison](../../system/comparison/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)