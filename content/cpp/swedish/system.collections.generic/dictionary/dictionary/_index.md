---
title: Dictionary()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom ordbok.
type: docs
weight: 1
url: /sv/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() konstruktor

Skapar en tom ordbok.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) konstruktor

Kopierar data från karta.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Karta att kopiera data från. |

## Dictionary::Dictionary(int) konstruktor

Överlagring som motsvarar att skapa en förallokerad ordbok; allokerar faktiskt inget.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| capacity | int | Kapacitet att allokera; ignoreras. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) att kopiera data från. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Källordbok. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) objekt att använda. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Skapar en tom ordbok.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) att använda. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Skapar en tom ordbok.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| capacity | int | [Dictionary](../) kapacitet efter skapande; ignoreras. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) att använda. |

## Se även

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Dictionary](../)
* Klass [IDictionary](../../idictionary/)
* Klass [IEqualityComparer](../../iequalitycomparer/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)