---
title: SortedList()
second_title: Aspose.Slides C++ API hivatkozás
description: Üres listát hoz létre.
type: docs
weight: 1
url: /hu/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() konstruktor


Létrehozza az üres listát.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) konstruktor


Létrehozza az üres listát.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) a használathoz. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor


Másoló konstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) a másolandó adatok forrása. |

## SortedList::SortedList(const map_t\&) konstruktor


Másoló konstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | A map a másolandó adatok forrása. |

## SortedList::SortedList(int) konstruktor


Létrehozza az üres listát.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| capacity | int | Az elemek száma, amelyet előre lefoglal. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)