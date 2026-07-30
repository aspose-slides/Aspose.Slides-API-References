---
title: Dictionary()
second_title: Aspose.Slides pro C++ - Referenční příručka API
description: Vytvoří prázdný slovník.
type: docs
weight: 1
url: /cs/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() konstruktor

Vytvoří prázdný slovník.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) konstruktor

Zkopíruje data z mapy.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mapa, ze které se kopírují data. |

## Dictionary::Dictionary(int) konstruktor

Přetížení, které odpovídá vytvoření předalokovaného slovníku; neprovádí alokaci.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| capacity | int | Kapacita k přidělení; ignorováno. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor

Kopiovací konstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) ke kopírování dat z. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Kopiovací konstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) objekt, který se použije. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Vytvoří prázdný slovník.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) k použití. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Vytvoří prázdný slovník.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| capacity | int | [Dictionary](../) kapacita po vytvoření; ignorována. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) k použití. |

## Viz také

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Dictionary](../)
* Třída [IDictionary](../../idictionary/)
* Třída [IEqualityComparer](../../iequalitycomparer/)
* Obor názvů [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)