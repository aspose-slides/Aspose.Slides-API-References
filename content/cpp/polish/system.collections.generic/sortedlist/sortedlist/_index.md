---
title: SortedList()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy pustą listę.
type: docs
weight: 1
url: /pl/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() konstruktor

Tworzy pustą listę.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) konstruktor

Tworzy pustą listę.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) do użycia. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor

Konstruktor kopiujący.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) do skopiowania danych z. |

## SortedList::SortedList(const map_t\&) konstruktor

Konstruktor kopiujący.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mapa do skopiowania danych z. |

## SortedList::SortedList(int) konstruktor

Tworzy pustą listę.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| capacity | int | Liczba elementów do zarezerwowania. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Klasa [SortedList](../)
* Klasa [IComparer](../../icomparer/)
* Klasa [IDictionary](../../idictionary/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)