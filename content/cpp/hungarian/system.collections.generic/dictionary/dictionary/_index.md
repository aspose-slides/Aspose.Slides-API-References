---
title: Dictionary()
second_title: Aspose.Slides for C++ API Referenciája
description: Üres szótárat hoz létre.
type: docs
weight: 1
url: /hu/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() konstruktor

Üres szótárat hoz létre.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) konstruktor

A map-ból másol adatokat.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map, amelyből az adatokat másolja. |

## Dictionary::Dictionary(int) konstruktor

Az a túlterhelés, amely előre lefoglalt szótár létrehozásának felel meg; valójában nem végez memóriakiosztást.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| capacity | int | A lefoglalandó kapacitás; figyelmen kívül hagyva. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor

Másoló konstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) az adatmásoláshoz. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Másoló konstruktor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Forrás szótár. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Használandó [Comparer](../../comparer/) objektum. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Üres szótárat hoz létre.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Használandó [Comparer](../../comparer/). |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) konstruktor

Üres szótárat hoz létre.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| capacity | int | A létrehozás utáni [Dictionary](../) kapacitás; figyelmen kívül hagyva. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Használandó [Comparer](../../comparer/). |

## Lásd még

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Dictionary](../)
* Osztály [IDictionary](../../idictionary/)
* Osztály [IEqualityComparer](../../iequalitycomparer/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)