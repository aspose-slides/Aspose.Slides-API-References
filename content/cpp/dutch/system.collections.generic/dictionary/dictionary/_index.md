---
title: Dictionary()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een leeg woordenboek aan.
type: docs
weight: 1
url: /nl/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() constructor

Maakt een leeg woordenboek aan.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) constructor

Kopieert gegevens van de map.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map waaruit gegevens worden gekopieerd. |

## Dictionary::Dictionary(int) constructor

Overload die overeenkomt met het maken van een vooraf gealloceerd woordenboek; voert in werkelijkheid geen allocatie uit.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| capacity | int | Capaciteit om te alloceren; genegeerd. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor

Kopieerconstructor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) om gegevens van te kopiëren. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor

Kopieerconstructor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Bronwoordenboek. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) object om te gebruiken. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor

Maakt een leeg woordenboek aan.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) om te gebruiken. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor

Maakt een leeg woordenboek aan.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capaciteit na creatie; genegeerd. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) om te gebruiken. |

## Zie ook

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Dictionary](../)
* Klasse [IDictionary](../../idictionary/)
* Klasse [IEqualityComparer](../../iequalitycomparer/)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)