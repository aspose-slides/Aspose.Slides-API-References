---
title: SortedList()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří prázdný seznam.
type: docs
weight: 1
url: /cs/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() konstruktor


Vytvoří prázdný seznam.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) konstruktor


Vytvoří prázdný seznam.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) k použití. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor


Kopírovací konstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) pro kopírování dat z. |

## SortedList::SortedList(const map_t\&) konstruktor


Kopírovací konstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mapa pro kopírování dat z. |

## SortedList::SortedList(int) konstruktor


Vytvoří prázdný seznam.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| capacity | int | Počet prvků, které se mají rezervovat. |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [map_t](../map_t/)
* Třída [SortedList](../)
* Třída [IComparer](../../icomparer/)
* Třída [IDictionary](../../idictionary/)
* Obor názvů [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)