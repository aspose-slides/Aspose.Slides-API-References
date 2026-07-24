---
title: SortedList()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert leere Liste.
type: docs
weight: 1
url: /de/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() Konstruktor


Konstruiert leere Liste.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) Konstruktor


Konstruiert leere Liste.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) zur Verwendung. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) Konstruktor


Kopierkonstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) zum Kopieren der Daten von. |

## SortedList::SortedList(const map_t\&) Konstruktor


Kopierkonstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map, aus der Daten kopiert werden. |

## SortedList::SortedList(int) Konstruktor


Konstruiert leere Liste.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| capacity | int | Anzahl der zu reservierenden Elemente. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)