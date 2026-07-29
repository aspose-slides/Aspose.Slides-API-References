---
title: SortedList()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom lista.
type: docs
weight: 1
url: /sv/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() konstruktor

Skapar en tom lista.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) konstruktor

Skapar en tom lista.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) att använda. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) att kopiera data från. |

## SortedList::SortedList(const map_t\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Karta för att kopiera data från. |

## SortedList::SortedList(int) konstruktor

Skapar en tom lista.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| capacity | int | Antal element att reservera. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Klass [SortedList](../)
* Klass [IComparer](../../icomparer/)
* Klass [IDictionary](../../idictionary/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)