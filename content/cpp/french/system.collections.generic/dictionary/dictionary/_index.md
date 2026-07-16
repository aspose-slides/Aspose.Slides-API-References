---
title: Dictionary()
second_title: Référence API Aspose.Slides pour C++
description: Crée un dictionnaire vide.
type: docs
weight: 1
url: /fr/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() constructeur

Crée un dictionnaire vide.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) constructeur

Copie les données du map.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map à copier les données. |

## Dictionary::Dictionary(int) constructeur

Surcharge correspondant à la création d'un dictionnaire pré-alloué ; ne fait en fait aucune allocation.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| capacity | int | Capacité à allouer ; ignorée. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructeur

Constructeur de copie.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) à copier les données. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructeur

Constructeur de copie.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) objet à utiliser. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructeur

Crée un dictionnaire vide.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) à utiliser. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructeur

Crée un dictionnaire vide.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capacité après création ; ignorée. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) à utiliser. |

## Voir aussi

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)