---
title: SortedSet()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy pusty zestaw.
type: docs
weight: 1
url: /pl/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() konstruktor

Tworzy pusty zbiór.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) konstruktor

Tworzy pusty zbiór o określonej pojemności.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) konstruktor

Tworzy pusty zbiór, który używa określonego porównywacza równości.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) obiekt do powiązania z [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor

Tworzy [SortedSet](../) na podstawie wartości wyliczalnych.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [SortedSet](../)
* Klasa [IComparer](../../icomparer/)
* Klasa [IEnumerable](../../ienumerable/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)