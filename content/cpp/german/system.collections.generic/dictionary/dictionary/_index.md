---
title: Dictionary()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein leeres Wörterbuch.
type: docs
weight: 1
url: /de/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() Konstruktor

Erstellt ein leeres Wörterbuch.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) Konstruktor

Kopiert Daten aus der Map.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map, aus der die Daten kopiert werden. |

## Dictionary::Dictionary(int) Konstruktor

Überladung, die dem Erstellen eines vorab zugewiesenen Wörterbuchs entspricht; führt tatsächlich keine Zuweisung durch.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| capacity | int | Kapazität, die zuzuweisen ist; ignoriert. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) Konstruktor

Kopierkonstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) zum Kopieren von Daten. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) Konstruktor

Kopierkonstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Quellwörterbuch. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) Objekt zum Verwenden. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) Konstruktor

Erstellt ein leeres Wörterbuch.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) zum Verwenden. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) Konstruktor

Erstellt ein leeres Wörterbuch.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| capacity | int | [Dictionary](../) Kapazität nach Erstellung; ignoriert. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) zum Verwenden. |

## Siehe auch

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)