---
title: HashSet()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Informacje RTTI.
type: docs
weight: 1
url: /pl/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() konstruktor

Informacje RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Uwagi

Tworzy pusty zbiór. 

## HashSet::HashSet(int) konstruktor

Tworzy pusty zbiór o określonej pojemności.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) konstruktor

Tworzy pusty zbiór wykorzystujący określony komparator równości.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) obiekt do powiązania z hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor

Tworzy hashset na podstawie wartości enumerable.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [HashSet](../)
* Klasa [IEqualityComparer](../../iequalitycomparer/)
* Klasa [IEnumerable](../../ienumerable/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)